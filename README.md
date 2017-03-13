# .Net Workshop | University of Moratuwa - CSE | Setup Guide

## Prerequisits
You must install the following software before the .Net Workshop
* Visaul Studio 2015 Community Edition - [Download](https://www.microsoft.com/en-us/download/details.aspx?id=48146)


## Example Project

We will use an example project through out the .Net Workshop to explain the concepts and the techniques. It's is a **mandatory** that you have the required software packages installed on your personal computers and follow the **Step-by-Step Guide** found bellow to start creating the example project. 

**You must:**
> complete the Example Project up to the point described in the Step-by-Step Guide to successfully follow along with the .Net Workshop agenda.
> The instructions are easy to understand and follow along.


# Step-by-Step Guide | Student Registration Application

## Step 01

Open Visual Studio 2015 Community Edition from the Start Menu or the Desktop Shortcut. Then, click on `File > New > Project` Menu Item. You will see the *New Project* dialog box where you can create a new Visual Studio Project.

There are a lot of project types to choose from, but for this Workshop we will focus on creating a **Windows Forms Application**. Select Windows Forms Application template under the `Visual C# > Windows` category on the left hand side of the New Project dialog.

>**Tip:**
> You can also search for installed templates by using the Search box on the top right corner of the New Project dialog box

After selecting the *Windows Forms Application* from the templates type in **StudentRegistration** as the *Name* of the project. Your screen should look something like this.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/1.png)

Click **OK** and create the project. After the project is created you will be presented with a screen similar to the screenshot bellow.

> **Note:**
> Don't worry if you are not familiar with the User Interface of Visual Studio. Most of the important aspects of Visual Studio will be covered during the workshop.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/2.png)

## Step 02

You can see the project structure on the *Solution Explorer* on the right hand side and `Form1.cs` file open in the left hand side of Visual Studio. Let's rename this Form1.cs file to a more meaning full name.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/3.png)

`Right Click` on the Form1.cs file on the Solution Expolrer and select `Rename` on the menu that pops up. Then Rename `Form1.cs` to `MainForm.cs` and press Enter. You will be presented with a message box informing you about updating the references according to the filename change. See the image bellow

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/4.png)

You need to accept the changes. Click on the **Yes** button to *automatically* do the reference updates. Now you will see that `Form1.cs` is renamed to `MainForm.cs`. 

Now let's make the form a little bit bigger. When you hover your mouse pointer on the bottom right corner of the form that is open your curser should change to a *double sided arrow*. Click and drag the form to make it a little bigger. You can make the form any size you like.

Now your screen should look something like this.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/5.png)


## Step 03

It's time to change some properties of the `MainFrom` or the Student Registration Application we are building. For this you need to select the MainForm on the designer, and then on the menu bar click on `View > Properties Window` to get the *Properties* window. See the screenshot below.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/6.png)

> **Tip:**
> You can also press `Ctrl + W` and then `Ctrl + P` keyboard combination to bring up the Properties Window

In the *Properties Window* you need to change the following Properties, to the given values.

* **Text** - Student Registration
* **StartPosition** - CenterScreen
* **ShowIcon** - False
* **MinimizeBox** - False
* **FormBorderStyle** - FixedSingle

>**Tip:**
>You can click on the property name in the *Properties Window* to see a small discription of what that specific Property does.

See the screenshot below, You can see the Text Property of the MainForm is changed to *Student Registration*

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/7.png)


## Step 04

It's time to add some User Interface elements to the *MainForm* of our application. To do that we need to open up the **Toolbox Windows** that constains all the User Interface elements supported for Windows Forms Application.

To bring up the *Toolbox* Windows, like we did for the Properties Window, on the Menu bar, click on `View > Toolbox` menu item. You will see a Toolbox Window pop up on the Visual Studio IDE.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/8.png)

> **Tip:**
> You can also press `Ctrl + W` and then `Ctrl + X` keyboard combination to bring up the Properties Window

First you need to add a *Label* to the MainForm of the application. Seach for *Label* in the Toolbox by scrolling up/down and `Click and Drag` a Label on to the MainForm to place the label on the Form. You can drag and drop any where you like. 

Look at the screenshot below to see where to place the *Label*

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/9.png)

> **Tip:**
> You can also *Search* for any UI element in the toolbox using the Seach box on the top of the toolbox.

After droping the label on to the *MainForm* change the `Text` Property of the *Label* from the *Properties Window* to *First name*. Now you can see the label has the First name text applied to it. Look at the screenshot below.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/10.png)

Then you need to add a `TextBox` to enter the First name. Search for *TextBox* in the *Properties Window* and drag and drop the `TextBox` on to the MainForm. You can resize it if you want. 

Next you need to change the **Name** Property of the `TextBox`. This *Name* property is used to get a reference (or to access the TextBox) from the C# code behind the MainForm. You will see this later.

Select the `TextBox` and Change the `Name` to *tbxFirstName* in the Properties Window. See the screenshot below.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/11.png)

Now, add one more `Label` and a `TextiBox` to the MainForm for the Last name. Change the `Label` *Text* to *Last name* and change the *Name* of the `TextBox` to *tbxLastName*. 

You should get something similar to the below screenshot.

![New Project Dialog](https://github.com/kasunkv/UoM-CSE-DotNet-Workshop-2017/blob/master/Screenshots/12.png)