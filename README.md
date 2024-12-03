# Active Directory Home Lab Part 3: Group Policy Objects

<h2>Description</h2>
In this Active Directory Home Lab, created a background image and set it for the engineering department group.  
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows GUI</b>

<h2>Environments Used </h2>

- <b>Windows Server 22</b> 
- <b>Windows 11 Enterprise</b> 
<br />
<br />
Create a background for the engineering department or download something form google. I deployed my art skills.

![1) create generic background in paint](https://github.com/user-attachments/assets/064890cc-4e6c-4868-9bf0-7db20d362b69)

<br />
<br />
Select "File and Storage Services".

![2) sleect file and storage services](https://github.com/user-attachments/assets/70cbed06-95ea-4394-a185-1c434492f49d)

<br />
<br />
Click Shares>NETLOGON>edit.

![3) select shares then netlogon then edit](https://github.com/user-attachments/assets/07c4a9f8-69ef-4478-877a-47e1b7571afa)

<br />
<br />
Drag and drop the saved backgorund image into the NETLOGON share for the domain. 

![4) copy background image into file directory of netlogon](https://github.com/user-attachments/assets/f65b5dd2-bcf1-4564-abdc-5887594d8ed5)

<br />
<br />
Next go to tools>Group Policy Management.

![5) copy file path of netlogon background image and go to group policy managment](https://github.com/user-attachments/assets/097fb8ff-fac6-45f5-a9b0-418f736cef80)

<br />
<br />
Within GothamCity.local domain go to the Engineering department and create a Group Policy Object.

![6) create GPO in engineering domain](https://github.com/user-attachments/assets/32bd189e-0f9c-42e0-8017-94e6c8ffa704)

<br />
<br />
The GPO I created was called "Set Engineering Background" then clicked edit.

![7) create set engineering background and edit](https://github.com/user-attachments/assets/30e8ec29-2330-443c-990c-f11d62bb567f)

<br />
<br />
Within the "Set Engineering Domain" GPO, navigate to User Configuration>Policies>Adminstrative Temp...>Desktop>Desktop>Desktop Wallpaper>right click edit.

![8) add desktop wallpaper](https://github.com/user-attachments/assets/2fec3654-4672-408b-b66d-e8bb5ee7ab5a)

<br />
<br />
Click enabled, and copy/paste the path to the bachground image within NETLOGON. 

![9) click enabled and paste path to wallpaper in netlogon](https://github.com/user-attachments/assets/6331e83b-6bf0-4570-a675-ad94cdfa1808)

<br />
<br />
Logged into Bruce Wayne Engineer User on Windows 11 Enterprise VM to see the background change.

![10)logged into Batman user in engineering to check bg](https://github.com/user-attachments/assets/285afef3-0918-4e1f-970d-da5de2ba407b)

<br />
<br />
