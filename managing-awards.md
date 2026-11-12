# Managing Awards on the [NCR Award Portal](https://portal.ncr.ac.uk/)

## Creating an Award

1. Log into the [NCR Award Portal](https://portal.ncr.ac.uk/) using your account.
2. Navigate to the **Allocators** page and select the appropriate allocator.
3. Click the **Awards** tab.
4. Click the **Add** button to create a new award.
5. In the pop-up, fill in the details:
   - **Award Name**
   - **Award End Date**
   - **Award Description** (if available)
   - **Project Shortname** (must be unique)
6. Click **Create**. The portal will automatically take you to the award dashboard once it is created.
7. From the award dashboard, go to the **Resources** tab. Click **Add** to add a new resource. Choose **Isambard 3** from the appropriate **Allocatable Offerings** section. This opens the Offering page — click **Create** to create the offering with default settings. It will take 10–20 seconds to create.
8. Once created, click **Options** in the middle/top menu to see the resource options. You should see the **Allocation** with a default value of node hours. Click the **Edit** button on the right to open the dialog and change the allocation to match the size of the award. Click **Save**.

You have now added all necessary information except the PI/membership details.

---

## Adding the PI

Go to the award dashboard and verify the details look correct (award name, description, and node hours allocation).

1. Click the **Team** tab, then click **Add**, then **Invite by mail**.
2. Enter their email and select their **Role** (e.g. **Project Lead**) from the drop-down.
3. Click **Continue**. This sends the user an email inviting them to log in and join the award.

The award is now created and the PI (Project Lead) has been added. This information will be communicated to the Bristol Portal, where it must be approved before the project is onboarded. Once onboarded, the Project Lead will be able to log in to the Bristol Portal, set up their account and access the cluster.

---

## Restricting Invitations through Membership Control and Setting Embargo Dates

### Membership Control

By default, Project Leads can invite users from any domain. You can restrict this for an award so that Project Leads can only invite users through the NCR Award Portal, and not through the site portals (such as the Bristol Portal).

1. Navigate to the **Allocators** page, select the appropriate allocator and open the **Remotes** tab.
2. Find the award you created and open the **actions** menu on the right-hand side of that award.
3. Set **membership control** to **locked**. This makes the award the source of truth for project membership, and stops Project Leads from inviting users on the site portals.
4. To choose which domains users are allowed to join from, select the **Set allowed domains** option and add the domain(s). For example, adding `*.ac.uk` allows anyone with an email address ending in `ac.uk` to join the award.

### Embargo Dates

You can create an award so that the resource/project is only created at the site on a particular date.

1. Open the **Remotes** tab for the appropriate allocator.
2. Open the **actions** menu for the award and select **Set embargo**.
3. Select the date on which you want the project to be onboarded and the resources to become available to users.

---

## Adding Top-Ups or Extensions

### Extending the End Date

1. Go to the award dashboard in the [NCR Award Portal](https://portal.ncr.ac.uk/).
2. Click **Edit** at the top to edit the award details.
3. Click the **Edit** button to the right of the **End Date** field. Choose the new end date and click **Save**. The change will be communicated automatically to the Bristol Portal, which will update the project there too.

### Adding Additional Node Hours

1. Go to the award dashboard in the [NCR Award Portal](https://portal.ncr.ac.uk/).
2. Click the **Resources** tab.
3. Click **Isambard 3** to go to the resource page.
4. Click **Options** in the middle/top menu to see the resource options. You should see the **Allocation** with the current allocation value.
5. Click the **Edit** button on the right. Change the allocation to the **total new allocation** (i.e. current value plus the top-up). Click **Save**. This will automatically send an update request to the Bristol Portal. The node hours will get applied to the project when someone approves this on the Bristol Portal.
