# Basics

1. Gathering Information
2. Identify Changes
  * Device Added?
  * New Program Installed?
3. Backup Data if not recent backups
4. Establish a Theory
  * Power Cords, Connnections, Comnon User Errors
5. Test Your Theory
6. Create an Action Plan
7. Wrap Up
  * Ensure Satisfaction
  * Document Findings

## For Testing

### Identify The Problem
Identification is often the easiest step. It may be accomplished via an inbound phone call from a user, a help desk ticket, an email message, a log file entry or any number of other sources. It is not at all uncommon for users to alert you to the problem.
It’s important to recognize that the root cause of specific issues is not always apparent. For example, a failed login attempt might seem to indicate a username or password problem, when instead the real issue may be a lack of network connectivity that prevents the authentication information from being checked against a remote server.

As troubleshooters, you want to be very careful to ensure you have identified the root cause of the error, misconfiguration or service interruption before making any changes.

Specific steps here may include:

Gathering information from log files and error messages
Questioning users
Identifying symptoms
Determining recent changes
Duplicating the problem
Approaching multiple problems one at a time
Narrowing the scope of the problem

### Establish a Theory of Probably Cause
	
Words such as theory and probable indicate a guess on your part, even if it is a guess backed by data. Keep in mind that the root cause (as determined in identifying the problem) may not have been accurately identified. However, the cause is specific enough to begin troubleshooting.

This step may require significant research on your part. Vendor documentation, your organization’s own documentation, and a good old-fashioned Google search may all be required to provide the basis for your theory.

Specific steps here may include:

Questioning the obvious
Considering multiple approaches, including top-to-bottom or bottom-to-top for layered technologies (such as networks)

### Test the Theory to Determine the Cause

Notice that the first two steps don’t require you to make configuration changes. Changes should not be made until you are reasonably sure you have a solution that you’re ready to implement.

This step is also part of the “information-gathering” phase.

It is not uncommon for experienced administrators to move very quickly and informally through steps one, two and three. Problems and symptoms are often familiar, making it simple to predict the likely cause of an error message or failed device.

At this stage, you may find yourself circling all the way back to step one: Identify the problem. If you test your theory to discover the likely cause and find that you were incorrect, you may need to start your research all over again. You can check in with users, dig more deeply into log files, etc.

Once you’re confident you’ve found the fundamental issue, the next step is to prepare to solve the problem.

### Establish a Plan of Action and Implement the Solution

If you believe you know the root cause of the troubleshooting issue, you can now plan how to address it. Here are some reasons to plan ahead before blindly jumping into a course of action:
Some fixes require reboots or other more significant forms of downtime
You may need to download software, patches, drivers or entire operating system files before proceeding
Your change management procedures may require you to test modifications to a system’s configuration in a staging environment before implementing the fix in production
*You may need to document a series of complex steps, commands and scripts
*You may need to back up data that might be put at risk during the recovery
*You may need approval from other IT staff members before making changes
Once you’ve completed this stage, you’re now ready to do whatever it is you believe you need to do to solve the problem.

These steps may include:

Run your scripts
Update your systems or software
Edit configuration files
Change firewall settings
Make sure that you have a rollback plan in place in case the fix you’re attempting does not address the issue. You must be able to reverse your settings to at least get back to where you began.

In some cases, implementing the proposed fix may be quicker than the research phases that preceded it. Those research phases are essential, however, to make sure you’re addressing the real issue and to minimize downtime.

### Verify Full System Functionality and Implement Preventive Measures	

When possible, have the users that rely on the system test functionality for you. They are the ones that really know how the system is supposed to act and they can ensure that it responds to their specific requirements.
Depending on the problem, you may need to apply the fix to multiple servers or other devices. For example, if you’ve discovered a problem with a device driver on a server, you may need to update the drivers on several servers that rely on the same device.

### Document Findings

Documenting your troubleshooting steps, changes, updates, theories and research could all be useful in the future when a similar problem arises (or when the same problem turns out not to have been fixed after all).

Another reason to keep good documentation as you go through the entire methodology is to communicate to others what you have tried so far. Such documentation is also useful in case your changes had unintended consequences. You are more easily able to reverse your changes or change configurations if you have good documentation on exactly what you did.
