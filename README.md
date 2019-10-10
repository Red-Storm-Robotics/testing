# testing
Repository for testing stuff and making sure everyone has their toolchain set up right

## Here's some useful stuff to know about ATOM, PROS, and Git

If you're using the "PROS Editor", you're actually using the Atom editor
with some add-ons that let you use PROS. (You can install more add-ons if you
want as well!)

If you're looking at this file through your web browser, you're not quite done.
You need to "clone" the repository to your computer. You can do this by opening
up Atom, clicking the icon in the top row with the three horizontal lines,
typing "GitHub Clone" in the search box and clicking on "GitHub Clone."

Under "Clone From", type in the web address of this repository (which is https://github.com/Red-Storm-Robotics/testing),
then click "Clone." The repository should appear on your computer. You should see
the files show up on the left side of your screen. You'll see many directories
such as "firmware", "include", "bin", and "src".

Atom has a setting in Edit->Preferences->Editor called "Atomic Soft Tabs."
This can help keep code indentation looking good.

You can use the functions in the PROS tab to build/compile and upload code,
among other things (such as creating a new project).

The Atom editor is made by GitHub. Because of this, it works really well with
GitHub. In the lower-right corner of the screen, there's a button that says
"GitHub." You should be able to log in with your GitHub account, and then you'll
see a "Git" tab and a "GitHub" tab.

You will be spending most of your time in the GitHub tab. If you make changes to
a file, you'll see the changes appear in the "Unstaged Changes" tab. (You might
also see some weird files you don't recognize, don't worry about them.)

You can push the "Stage All" button to stage these changes. Once the changes are
staged, it's time to commit them. Enter a message in the Commit Message box that
describes your changes, and click "Commit to master".

However, you'll still need to push your changes. At the bottom, to the left of the "GitHub" button,
there's a button labeled either "Fetch", "Push", "Pull", or something like that.
Clicking it will synchronize the code on your computer to the code on GitHub.

You'll notice the directories "firmware", "include", "bin", and "src" on the left
side of your screen. "src" is where the source code goes. These are the `.cpp` files
that contain C++ code. "include" is where the header files (`.h` files) go. You
shouldn't need to modify the other directories; they are used to compile and upload
your code.

This was kind of an "information dump", and there are probably things I forgot
to mention. If you have any questions, reach out to me! And don't be afraid to
mess around here (try adding some code, and then staging, committing, and pushing
your changes!)
