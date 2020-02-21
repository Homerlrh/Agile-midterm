# midterm

---

## git clone

> Git clone will create a newly repo in the local. It sets up a local branch bases on the remote branch, and if you type git log you will see the all the commit history. Also you will have all teh remote-traching for all the remote branch as well.

## Example

> clone the repo when you want to be a contributer

> Cloning a repo is useful when you want a copy of repo, though you may not contribute in the future.

---

## git fetch

> git fetch only downloads new data from the remote repo, it does not integrate any of this new data into working files directory.

## Example

> When you want to know what is ejs, you should fetch it

> git fetch is good when you want to know all the thing in that repo. Fetch will never manipulate, destory or mess up the repo.

---

## git pull

> To update your current local branch with the lasest commit form the remote branch. It not only download the data, it also integrate them (merge)

## Example

> Before you push, pull it first. To avoid as much as merge conflict

> If you working in a group,before you push the code to the repo, you should pull all the latest changes and make sure there will not be any merge conflict.

---

# Section 2

|      | Trello                                                         | Asana                                                 |
| ---- | -------------------------------------------------------------- | ----------------------------------------------------- |
| Pros | Free to use                                                    | Free to use for teams up to 15 people.                |
| ^    | Kanban-style boards                                            | Cross platform                                        |
| ^    | easy to use, user friendly                                     | Integration with email, Zapier and more.              |
| ^    | Integrations available with tools like Slack and Google Drive. | A single task can be linked to more than one project. |
| Cons | Export feature only available with a premium subscription.     | No two-factor authentication.                         |

---

# Third Section: Answer the following 3 questions:

#### Question 1: What is the .git folder? Where is the object database in this folder?

> The .git file contain all the information of the remote branch such as version control and all the information about commits, remote repository address.In the Object folder and store as a blob object.

#### Question 2: Explain in detail how the git hash-object function works.

> Git hash-object would take the content you handed to and return a unique key that would be suer to store in git database. The -w option then tells the command to not simply return the key, but to write that object to the database.

> From stackoverflow, git prefixes the object with "blob ", followed by the length (as a human-readable integer), followed by a NUL

#### Question 3: Where does git internally store the file names to our files? How are tree objects related to this?

> git creates a folder call .git and store everything in it. Git does not store the any filename in the file, because blob don't store any file name. Tree Objects in git represent directories. Each tree may contain BLOBs and other Trees. Therefore, we can use the BLOBs id for the filename
