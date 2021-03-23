---
author: [Alfresco Documentation, Alfresco Documentation]
audience: 
option: 
---

# Publishing content

Publishing in the Web Quick Start site is based on a workflow driven model. Once site content associated with a workflow task is approved, a copy of the content is promoted from the Quick Start Editorial folder to the Quick Start Live folder.

There are two workflows available in Share that can be used for publishing. Both options promote content to the Live folder. They are:

-   **Review and Publish Section Structure**

    Enables you to review and publish the structure of a section of the website

-   **Review and Publish**

    Enables you to review and publish web content


The **Review and Publish Section Structure** workflow enables you to easily publish the structure of a specific section of the library by initiating this workflow on the **index.html** file for the desired section. This workflow publishes the structure of the selected section, its **collections** folder, and all of its subsections. This workflow does not publish the content contained within the sections to the Live folder; you must use the **Review and Publish** workflow to publish content items.

**Note:** To publish the structure of the entire Quick Start Editorial branch, initiate the **Review and Publish Section Structure** workflow on the **index.html** file for the **root** section.

The **Review and Publish** workflow enables you to publish individual assets. You can select a single asset or a group of assets to publish at one time.

**Note:** This task walks you through the specific example of publishing the site structure and individual web assets.

This task assumes you are in the Document Library page component of the Quick Start site and that the **Show Folders** feature is enabled.

1.  Navigate to **Alfresco Quick Start \> Quick Start Editorial \> root**.

2.  Locate **index.html** and click **More**, then **Start Workflow**.

3.  On the Start Workflow page, expand the list provided and select **Review and Publish Section Structure**.

    A workflow form displays where you enter the details of the workflow task being initiated.

4.  Complete the form as appropriate.

    **Note:** Only the Reviewer is required.

    1.  In the Message field, describe what you want the recipient of the task to do, such as Please review the attached content.

    2.  Click the icon to the right of the Due field to specify the date by which this task must be completed.

    3.  Click Select beneath Reviewer, then search for and select the site member you want to be responsible for the task generated by the workflow.

        This search requires a minimum of one \(1\) character; it is not case sensitive. You can provide a full or partial name.

        **Note:** If you have not created additional users for this installation of Share, you can simply assign the task to yourself to work through this feature.

    4.  Click **OK** to proceed.

5.  Click **Start Workflow**.

    The workflow task is created and you are returned to the content item list. An icon to the left of **index.html**indicates it is part of an active workflow.

6.  Navigate to your personal dashboard and locate the review task in the My Tasks dashlet.

7.  Click the **Edit Task** icon.

8.  On the Edit Task page, add a comment, if desired, and click **Publish**.

    The content associated with the workflow task is queued up for publishing to the Quick Start Live folder.

    **Note:** The publishing queue is processed once every minute by default, so it may take this long for the published content to appear in the Live site.

    The task then returns to the person who initiated the workflow to notify them that their request for approval was successful. The task can then be marked as complete.

9.  In your browser, navigate to the Quick Start Live environment.

    The default Web Quick Start configuration sets the Live website host to 127.0.0.1. Therefore, if you are running the Quick Start installation locally, you can view the live website on http://127.0.0.1:8080/wcmqs.

    Notice that the website structure is in place, including the navigation links along the top of each page. The website contains no content.

10. In Share, navigate to **Alfresco Quick Start \> Quick Start Editorial \> root \> blog**.

11. Locate **blog1.html** and click **More**, then **Start Workflow**.

12. For this second workflow task, select **Review and Publish**.

13. Complete the Start Workflow form as follows:

    1.  Add a message \(optional\) and specify a reviewer \(required\).

    2.  Click **Add** beneath the items list to display the Select page.

        The left side of this page displays the web assets in the **blog** folder. The right side displays the assets to be published.

    3.  Add the assets **blog2.html** and **blog3.html**.

    4.  Click **OK**.

14. Click **Start Workflow**.

    The workflow task is created and you are returned to the content item list. An icon to the left of **index.html** indicates it is part of an active workflow.

15. As you did with the previous workflow task, locate the review task in the My Tasks personal dashlet, click the **Edit Task** icon, and click **Publish**.

16. In your browser, open the Quick Start Live environment as in step 9 and click the **Blog** navigation link in the header.

    The Blogs page of the website displays the three articles you added to the workflow task for publishing.


**Parent topic:**[Using Alfresco Web Quick Start](../concepts/qs-intro.md)
