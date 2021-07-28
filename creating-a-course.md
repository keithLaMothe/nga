# Creating a Course

This guide is for Course Creators \(Site Administrators can also use it\).

General note: many steps take you through screens with a ton of other fields and options you can set, but you should usually leave them all as defaults to save time and improve consistency.

1. Log in to [https://nga.moodlehub.com/](https://nga.moodlehub.com/) .
2. On the left sidebar, click the `Site Home` button.
3. In the main area, under `Course categories`, click the category the course should be under \(or any category; you can choose later\)
4. In the middle of the main area, click `Add a new course`.
5. Under `General`, enter `Course full name` and `Course short name`.
6. For `Course category`, if it's not correct, remove the current selection and select the right category.
7. For `Course visibility`, select `Hide` \(you'll change that later when the course content is done\)
8. Set `Course start date` fields \(e.g. 1, August, 2021, 00, 00\).
9. Under `Description`, enter `Course summary`.
10. Under `Course format`, set `Number of sections` to 15 or however many weeks there are supposed to be in the course.
11. At the bottom of the page, click `Save and display`
12. In the upper right, if the button says `Turn editing on`, click it to switch into edit mode
13. The course content can be added in any order, but here's an example of how to add content: click the topmost `Add an activity or resource`, and then on the `Resources` tab, and then on `File` \(you can find Label on the All tab too, it's just more cluttered\).
14. For `Name`, type `Syllabus`.
15. Upload the syllabus file in the `Select files` field. Drag-and-drop is convenient, or you can click on the file area and then on `Upload a file`, `Choose File`, and `Upload this file`.
    * Note: if you'd prefer the syllabus be a web page instead of a file the user downloads/opens, that's also doable via the `Page` resource type.
16. At the bottom of the page, click `Save and return to course`.

Adding course content is basically a repetition of steps 13-16. Here's how to add the individual types of content we've discussed:

* **Welcome/header message**: click `Add an activity or resource` on the top section, select `Label`, enter `Label text`, and click `Save and return to course`.
  * Label text can be heavily formatted using the visual editor or by entering raw HTML \(click the down arrow in the upper-left corner of the Label text editor, then click the &lt;/&gt; button on the row that appears\).
* **Reading assignment**: Use the `Add an activity or resource` link on the week you want the assignment on, select `Checklist`, then:
  * Under `General` , enter `Checklist` \(e.g. "Week 1 Readings"\).
  * Under `Settings` , enter `Maximum Grade` \(e.g. "1"\)
  * Click `Save and display` .
  * It will automatically highlight the box for entering the first item, enter the first reading for that week \(e.g. "Book you should read, pp. 4-12"\) and click `Add`.
  * Add any further readings for that week, and then navigate back to the course \(by clicking the name at the top of the left sidebar, for example\) to continue adding other content.
* **Recorded video**: Select `Page`, then:
  * Under `General`, enter `Name`.
  * Under `Content`, in `Page content`, click the down arrow and then the `</>` button to switch to HTML input.
  * Replace the default HTML \(looks like `<p dir="ltr" style="text-align: left;"><br></p>`\) with the embed code for the video into the HTML input, example: `<div class="muse-video-player" data-video="njZPo2j" data-width="576"></div><script src="https://muse.ai/static/js/embed-player.min.js"></script>`
* **Discussion forum for a single recorded video**: add item to same week as the video, and select `Forum` \(this is on the Activities tab, not Resources\), then:
  * Under `General`, enter `Forum name` \(e.g. "Lesson 1 Discussion"\).
  * If you want the first "post" of the discussion to have some text, enter that in the `Description` field.
  * Change `Forum type` to `A single simple discussion`.
* **Discussion forum for the whole course**: add item to the top section, select `Forum`, and set `Forum type` to `Standard forum for general use`. You may prefer to use this and not the individual video discussions.
* **Live classroom**: Select `BigBlueButtonBN`, then:
  * Under `General settings`, enter `Virtual classroom name` \(e.g. "Session 1" or "8/3/2020 2pm EST class"\).
  * `Wait for moderator` is checked by default, and this prevent students from accidentally joining a session before the moderator is present. You can disable this if you want students to be able to join the meeting before the moderator arrives. If you do that, you may wish to set `Join open` and `Join closed` under `Schedule for session` to prevent students from joining the wrong session by accident.
  * `Session can be recorded` is checked by default, so you will be able to turn on \(and off\) the recording within the session, and the recording will become available to view on the session's page after it's done processing. Please note that if you do not press the record button during the session, the session will not be recorded.
* **Reflection paper**: Select `Assignment`, then:
  * Under `General`, enter `Assignment name` and `Description`.
  * Under `Availability`, enter `Due date` \(or disable it\), and optionally enter `Cut-off date` if you want it to be impossible to submit after that time.
  * If necessary, adjust `Remind me to grade by`.
  * Under `Submission Types`, if you want the students to be able to type their response directly into Moodle, check `Online text`. The default is just `File submissions`, and both can be allowed Bear in mind that online text is easier to "lose" if they accidentally close their browser or the computer turns off, etc.
  * If desired, under `Notifications`, set `Notify graders about submissions` and/or `Notify graders about late submissions` to Yes.
  * Under `Grade`, set `Type` to `Scale` and `Scale` to `Default competence scale`. This means that the assignment will be graded as either `Competent` or `Not yet competent`.
* **Quiz/Test/Final**: Select `Quiz`, then:
  * Under `General`, enter `Name` \(e.g. "Quiz 1"\).
  * If desired, under `Timing`, enter `Open the quiz` and/or `Close the quiz` to control when students can attempt it.
  * Under `Grade`, change `Attempts allowed` from Unlimited to 1.
  * If desired, under `Question` behavior, change `Shuffle within questions` to No, if you want the questions to be in the same order for each student.
  * Click `Save and display` and then `Edit Quiz` to proceed to enter individual questions.
  * On the right side, under the Shuffle checkbox, click `Add`, then `a new question`, and then select `Essay` and click `Add`.
  * Under `General`, enter `Question name` \(e.g. "1"\) and `Question text`.
  * If desired, change `Default mark` to something other than 1, if you want it to be weighted differently. So if you have a 3-mark question and a 1-mark question on a quiz with a max score of 10, the first question will be worth 7.5 and the other worth 2.5.
  * Under `Response options` , change `Response format` to `Plain Text` .
  * Click `Save changes`.
  * Click the `Add` -&gt; `a new question` links again to add more questions, until done  
    * Note: you can also add true/false, multiple choice, and other kinds of questions that are automatically graded.
  * When you're done adding questions, click the name of the quiz towards the top of the main content area \(on the same line as "Dashboard /"\), then click `Preview quiz now` to test it. After submitting, you can re-try it by clicking the `Start a new preview` button on the right sidebar.

Once you've added all the content and are ready for the course to be visible to students, click the gear icon in the upper right above the `Turn editing off` button, then click `Edit settings`, select `Show` for `Course visibility`, and finally click `Save and display` at the bottom of the page.

