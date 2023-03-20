<head><base target="_blank"> </head>

#### 1. Open an Automation

In the FME Server web interface, click Automations > Manage Automations on the left navigation panel.

![Manage Automations](./images/manage.png)

#### 2. View Automation Configuration

This Automation has a Schedule Trigger that causes it to run once day. You can see how this is configured by double-clicking the Schedule object on the canvas to open the Details pane. You can see it is set to run once a day.

![Schedule Trigger](./images/schedule.png)

After the Trigger activates, it will run the FoodVendors workspace. Double-click the orange Run a Workspace Action to view the Details pane. It shows the parameters being used to run the workspace. It will write the data to an FME Server Data folder.

#### 3. Start the Automation

If it's not already running, click the Start Automation button on the top-right side of the Automations page to turn it on.

![Trigger automation](./images/start.png)

Now it will run whenever the schedule triggers.


#### 4. Manually Trigger the Automation

So we don't have to sit around waiting, double-click the Schedule again and then click the Trigger button in the bottom right. This button lets you manually trigger Automations for testing.

![Trigger automation](./images/trigger.png)

#### 5. View Triggered Jobs

You can confirm the Automation ran the workspace by clicking Menu > View Triggered Jobs.

![Log](./images/view-jobs.png)

You should see one job where FoodVendors.fmw ran recently. You can click the Job to see the log.

![Log](./images/log.png)

Congratulations! You built an FME workspace and learned about creating data integration automations using FME Server.

#### 6. Continue to Next Exercise

Click the Next button below.