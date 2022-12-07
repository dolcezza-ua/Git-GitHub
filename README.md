# Git-GitHub

## JSON [repo](https://github.com/dolcezza-ua/JSON)

**1.** Create an external repository called JSON on GitHub. (`Create a new repository`)

- Clone the JSON repository to the local machine.

  - `$ git clone git@github.com:dolcezza-ua/JSON.git`

**2.** Inside the local JSON, create a “new.json” file.

- `$ touch new.json`

**3.** Add file under git.

- `$ git add new.json`

**4.** Commit the file.

- `$ git commit -m "add new.json"`

**5.** Submit the file to an external GitHub repository.

- `$ git push`

**6.** Edit the content of the “new.json” file - write information about yourself (full name, age, number of pets, future desired salary). Write everything in JSON format.

- `$ nano new.json`

**7.** Push changes to an external repository.

- `$ git commit -am "modify new.json"`

- `$ git push`

**8.** Create preferences.json file. In the preferences.json file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in JSON format.

- `$ cat > preferences.json`

```json
{
  "favorite_movie": "My_dogs",
  "favorite_series": "My_cats",
  "favorite_food": "ice_cream",
  "favorite_season": "spring",
  "dream_country": "France"
}
```

**9.** Create a file sklls.json and add information about the skills that will be studied on the course in JSON format.

- `$ cat > skills.json`

```json
{
  "programming_languages": "Pyton, JavaScript",
  "sniffing_web_traffic": "Charles, Fiddler",
  "database": "Postgres",
  "non-relational_database": "Redis",
  "load_testing": "Jmeter",
  "development_methodology": "Scrum"
}
```

**10.** Send 2 files at once to an external repository.

- `$ git add preferences.json skills.json`
- `$ git commit -m "add 2 files"`
- `$ git push`

**11.** On the web interface, create the bug_report.json file.(Add file ---> Create new file ---> Commit new file)

Make Commit changes (save) changes on the web interface.(Open file ---> Go to the pencil button Edit this file ---> Commit changes)

Modify the bug_report.json file on the web interface, add a bug report in JSON format.(Open file ---> Go to the pencil button Edit this file)

Make Commit changes (save changes) on the web interface.(Commit changes)

- Synchronize external and local JSON repository.
  - `$ git fetch`
  - `$ git pull`

---

## XML [repo](https://github.com/dolcezza-ua/XML)

**1.** Create an external repository called XML on GitHub.(Create a new repository)

- Clone the XML repository to the local machine.
  - `$ git clone git@github.com:dolcezza-ua/XML.git`

**2.** Inside the local XML create the “new.xml” file.

- `$ touch new.xml`

**3.** Add file under git.

- `$ git add new.xml`

**4.** Commit the file.

- `$ git commit -m "add new.xml"`

**5.** Submit the file to an external GitHub repository.

- `$ git push`

**6.** Edit the content of the "new.xml" file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in XML format.

- Push changes to an external repository.
  - `$ git commit -am "add changes to new.xml"`
  - `$ git push`

**7.** Create preferences.xml file.

- `$ touch preferences.xml`

**8.** In the preferences.xml file, add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in XML format.

- `$ nano preferences.xml`

**9.** Create a file sklls.xml add information about the skills that will be studied on the course in XML format.

- `$ nano skills.xml`

**10.** Make a commit in one line.

- `$ git add skills.xml preferences.xml | git commit -m "commit 2 files at once"`

**11.** Send 2 files at once to an external repository.

- `$ git push`

  **12.** On the web interface, create the bug_report.xml file. Make Commit changes (save) changes on the web interface.(Add file ---> Create new file ---> Commit new file)

  Modify the bug_report.xml file on the web interface, add a bug report in XML format.(Open file ---> Go to the pencil button Edit this file)

  Make Commit changes (save changes) on the web interface.(Commit changes)

- Synchronize external and local XML repository.
  - `$ git fetch`
  - `$ git pull`

---

## TXT [repo](https://github.com/dolcezza-ua/TXT)

**1.** Create an external repository called TXT.(Create a new repository)

- Clone the TXT repository to the local computer.
  - `$ git clone git@github.com:dolcezza-ua/TXT.git`

**2.** Inside the local TXT, create the "new.txt" file.

- `$ touch new.txt`

**3.** Add file under git.

- `$ git add new.txt`

**4.** Commit the file.

- `$ git commit -m "add new.txt"`

**5.** Submit the file to an external GitHub repository.

- `$ git push`

  **6.** Edit the contents of the "new.txt" file - write information about yourself (name, age, number of pets, future desired salary). Everything should be written in TXT format.

- `$ nano new.txt`

**7.** Push changes to an external repository.

- `$ git commit -am "add new.txt"`
- `$ git push`

**8.** Create preferences.txt file. Add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, side you would like to visit) in the file preferences.txt in TXT format.

- `$ cat >> preferences.txt`

Create a file sklls.txt add information about the skills that will be studied on the course in TXT format.

- `$ cat >> skills.txt`

* Make a commit in one line.
  - `$ git add preferences.txt skills.txt | git commit -m "add and commit 2 files at once"`

**9.** Send 2 files at once to an external repository.

- `$ git push`

**10.** Create a bug_report.txt file on the web interface.(Add file ---> Create new file ---> Commit new file)

Make Commit changes (save) changes on the web interface.(commit changes)

Modify the bug_report.txt file on the web interface, add a bug report in TXT format.(Open file ---> Go to the pencil button Edit this file)

Commit changes (save changes) on the web interface.(Commit changes)

- Synchronize external and local TXT repository.
  - `$ git fetch`
  - `$ git pull`
