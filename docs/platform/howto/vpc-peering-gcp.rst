Set up Virtual Private Cloud (VPC) peering on Google Cloud Platform (GCP)
=========================================================================

Once you've created a :doc:`VPC on the Aiven platform <manage-vpc-peering>`, you can follow these instructions to set up VPC peering on GCP.

1. Open your GCP Console.

2. Select **VPC Networks** and find the VPC that you want to connect to.

3. Click the project name and make note of the *Project ID*.

4. Under *VPC Networks*, make note of the VPC Network Name.

5. In `Aiven Console <https://console.aiven.io>`_, select **VPCs** from the sidebar on the **Services** page.

6. On the **Virtual private clouds** page, select the VPC connection that you created.

7. On the **VPC Peering connections** page, enter the project ID and VPC network name from GCP, then click **Add peering connection**.

   This adds a new connection with the *Pending Peer* status.

   .. note::

      Click the blue Pending peer icon and make a note of the Aiven project name and the network name.

8. In your GCP Console, go to **VPC** > **VPC network peering** and select **Create Connection**.

9. Enter a name for the peering connection, and enter the same project ID and network name that you found in step 7.

10. Click **Create**.

When the peering is successful, it is active in both `Aiven Console <https://console.aiven.io>`_ and your GCP Console.
