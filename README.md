Download Link: https://assignmentchef.com/product/solved-ve280-lab4
<br>
Haruhi enjoyed watching <em>Attack on Titan</em> together with Kyon. However, she got quite upset about the last chapter and believed that she could produce a much better work than Isayama Hajime. The cultural festival was just around the corner, so she decided to call up the members of SOS brigade and produce her own short movie <em>The Adventures of Mikuru Asahina Episode 00</em>.

This short movie is mainly about the war between Asahina Mikuru, a cute girl from the future, and Nagato Yuki, a silent, expressionless and inhospitable alien girl.

They need <strong>1 costume for Mikuru, 2 guns and 100 bullets</strong> for each scene.

Yamazaki’s Model Shop sells bullets and guns, and Omori’s Costume Store sells costumes.

<strong><u>Ex1. How Many Scenes Could They Produce?                                   </u></strong>

Related Topics: <em>exceptions</em>, <em>program arguments</em>.

For Ex1, you are going to simulate the process of purchasing the needed materials for the movie. The following are some basic rules:

They will first visit Omori’s Costume Store and then Yamazaki’s Model Shop . If

Yamazaki’s Model Shop is open, they will first buy guns and then buy bullets. During the procedure, if any “exception” happens (eg: Omori’s Costume Store is closed, bullets in

Yamazaki’s Model Shop are not enough, etc), the buying process will end (exception caught). See ex1.cpp for details.

The input will be a sequence of numbers read from <strong>program arguments</strong> (6 numbers in total):

number of scenes (int) status of Omori’s Costume Store (1 for open and 0 for closed) status of Yamazaki’s Model Shop (1 for open and 0 for closed), number of costumes remaining in Omori’s Costume Store (int) number of guns remaining in Yamazaki’s Model Shop (int) number of bullets remaining in Yamazaki’s Model Shop (int)

For example, if the program name is ex1 and the arguments are ” 3 1 1 10 5 355 “, i.e. ,

./ex1 3 1 1 10 5 355 then they will make 3 scenes, both stores are open, 10 costumes remain in Omori’s Costume Store , 5 guns and 355 bullets remain in Yamazaki’s Model Shop .

Part of the program has already been implemented. Your work is to complete the program by filling the parts marked with TODO . Please <strong>do not change</strong> any code that is already written. See ex1.cpp for further instructions.

Output is Kyon’s thoughts in his mind. Sample output for above example:

We visit Omori’s Costume Store first…

We’ve bought enough costumes! I can’t wait before Miss Asahina wears them! Then we visit Yamazaki’s Model Shop… Guns in Yamazaki’s Model Shop are not enough. We still need 1 more.

We have to wait longer before we get started. Fortunately, Miss Asahina can have more peaceful days.

<strong><u>Ex2. Which Bullet Should They Buy?                                                   </u></strong>

Related Topics: <em>IO</em>, <em>compound objects</em>, <em>program arguments</em>.

Different types of bullets are put in different types of boxes, with different prices. The number of bullets in different boxes may not be equal. Koizumi wanted to find the type of bullet with the best cost performance (the lower, the better). Please write a program to help him. Cost performance is calculated by &lt;total cost&gt;/&lt;number of bullets&gt;

In this exercise, you are going to read a file which contains all the price information for different kinds of bullets.

In each line, they have the same format:

&lt;type name (string ,no space)&gt; &lt;price (double)&gt; &lt;number of bullets (int)&gt; Here is an example:

Name your file as ex2.cpp .

Make sure to use file streams to read the file and structs to contain the information.

Output: Print the information of all of the bullet varieties with the best cost performance into stdout. The format and sequence (if there are two or more) should be the same as the input file.

Example output for above file:

For consistency, you can assume that all the price numbers in the file have 2 decimal places. In your output, the price and should have 2 decimal places as well.

<strong><u>Ex3. Guest list                                                                                            </u></strong>

Related Topics: <em>IO</em>.

Haruhi’s new movie was on. A great many otakus were attracted to watch it. Kyon was asked to collect the names of audiences watching that movie. But he found that currently the collection of the names was a mess like this.

Names were English letters, no space inside, separated by commas and spaces, but sometimes there are too many spaces between a name and a comma and sometimes there’s no space. Only 1 comma can appear between 2 names, but <strong>the number of spaces and the number of names are not fixed</strong>. He wanted to make a name list using the original name collection and the exact number of people.

Please write your code in a file named ex3.cpp . Here are the requirements:

The order of the names should be <strong>the same</strong> as in the input message. Each name or the number occupies one line.