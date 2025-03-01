Manage projects
===============

Create a project
----------------

In the `Aiven web console <https://console.aiven.io/>`_, follow these steps to create a new project:

1. Click on **Project** drop down and click on **Create new project**.
2. Give the new project a name.
3. Select an Account to add the project to.
4. In **Payment method** select a project to copy the billing details from, or select **Use a new credit card**.

When you create a new project, you will need to enable :doc:`billing for creating new services </docs/platform/howto/list-billing>`.

.. note::
    You can :ref:`create a project using the Aiven CLI <avn-create-update-project>` as well.


Rename a project
----------------

Renaming a project is possible **only** when all the services in the project are powered-off. To rename a project in the `Aiven web console <https://console.aiven.io/>`_:

1. Select the project from the **Project** drop down.
2. Click on **Settings**. 
3. Type in the new project name in the *Project Name* field.
4. Click on **Save changes**. 

.. important:: 
   
   - Except for Aiven for Apache Kafka®, all service types have backups which are restored once you power them back on.
   - Renaming the project will invalidate all of the project's pending invitations.
   - The project name in your existing DNS records will not be updated.

.. note::
    You can :ref:`rename a project using the Aiven CLI <avn-create-update-project>` as well.

Move a project
---------------

To move a project from one organizational unit to another:

#. Open the organizational unit that has the project using the drop-down menu in the top right.

#. Click **Admin**.

#. Select the **Projects** tab.

#. Find the project you want to move and click **Move project**.

#. Select the organizational unit that you want to move the project to.

   .. note:: 
        Projects cannot be moved to other organizations or to organizational units that are in other organizations.

#. Choose a billing group.

#. Click **Move project**.


Delete a project
----------------

To delete a project, you first need to delete all of the services in it. Once the services are deleted:

#. Select the project from the **Projects** drop down.

#. Click **Settings**.

#. Click **Delete project**. 

#. Click **Confirm**.

.. note::
    You can also :ref:`delete a project using the Aiven CLI <avn-delete-project>`.
