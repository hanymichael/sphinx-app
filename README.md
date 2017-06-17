The Sphinx Project is a Node.JS app wrapped in Express.JS. The purpose of this app is to demonstrate the VMware deployment details of Kubernetes on different platforms like vSphere, vRA, Photon Platform or NSX-T (to name a few).

The web application calls the os.hostname(); and os.networkinterfaces(); functions to get this information from the local linux container and render this through HBS to the end-user.
