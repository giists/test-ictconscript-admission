Keeping a physical paper logbook is slow and inefficient compared to a digitalized one. With an electronic logbook, all authorized parties can check the log in the
field with no need to go the physical location of the logbook, boosting awareness, efficiency, and security when implemented correctly.

The goal is to build an browser application that's easy and fast to use and deploy. The proof of concept version needs to be able to display entries made by other users, and have functionality to write new entries.
The log entries should appear instantly, and the app needs to be deployable easily on any hardware.

One developer and one px engineer manage the frontend side of things. The developer responsible for the frontend will be given the specs of how data is formatted from the backend dev. How the data is displayed is the
responsibility of the frontend dev and the px engineer.
The other developer is responsible for the backend, and is responsible for developing a REST service that stores and serves the log entries submitted by the browser app.
The infra engineer is responsible for making sure the stack is containerized, the deployment is automated, and that all traffic is encrypted. 
