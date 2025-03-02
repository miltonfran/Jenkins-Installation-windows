# Jenkins-Installation-windows
<h1>Create a Google Cloud Compute Engine</h1>

<h2>Description</h2>
The Microsoft Windows Jenkins MSI package comes complete with the Java Runtime Environment (JRE) prerequisite and Microsoft .NET 2.0 framework. This bundling provides a seamless Jenkins installation experience, and alleviates the need for any external prerequisite software installations.

By using the MSI installation package, the Jenkins installation wizard will automatically install itself as a Windows service. Running Jenkins as a Microsoft Windows service makes application management easier as Windows services provide an easy way to specify corrective steps in case of application crash.

<br />


<h2>Download the latest version of https://www.jenkins.io/download/ to a folder of your choice. </h2>

</b> <img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1740940158/Screenshot_2025-03-02_130345_kupcpv.png"/>
</b>
Unzip the file to a folder and double-click on the Jenkins exe file and follow the prompts to complete the installation.

This will set up Jenkins as a windows service. You can verify it by going to Start > Control Panel > Administrative Tools > Services.

Note that the Jenkins settings file is located at C:\Program Files\Jenkins\jenkins.xml. This is where you will modify Java and Jenkins options.
