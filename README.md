# cs-570-homework-assignment-6-solved
**TO GET THIS SOLUTION VISIT:** [CS 570-Homework Assignment 6 Solved](https://www.ankitcodinghub.com/product/cs-570-homework-assignment-6-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;72453&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;&nbsp;&nbsp; CS 570-Homework Assignment 6 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
&nbsp;

&nbsp;

1 Assignment Policies

&nbsp;

Under absolutely no circumstances code can be exchanged between students. Excerpts of code presented in class can be used.

&nbsp;

Assignments from previous offerings of the course must not be re-used. Viola-tions will be penalized appropriately.

&nbsp;

Late Policy. &nbsp;&nbsp;&nbsp; Check the course syllabus for the late submission policy.

&nbsp;

<h1>2 Assignment</h1>
&nbsp;

For this assignment, you will compute the list of words in a given dictionary that has the most number of anagrams. An anagram is word or phrase formed by rearranging the letters of a different word or phrase, typically using all the original letters exactly once. For example, “rail safety” and “fairy tales” are anagrams. In this assignment, to simplify matters, we will focus on anagrams of words formed from letters only. For example, here is a list of 15 anagrams of the word “alerts”, including “alerts” itself, taken from the dictionary:

&nbsp;

alerts, alters, artels, estral, laster, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; lastre, rastle, ratels, relast, resalt,

salter, slater, staler, stelar, talers

&nbsp;

This assignment requires the class Anagrams. We next describe the class through the following UML diagram:

1

Anagrams

&nbsp;

final Integer[] primes; &nbsp;Map&lt;Character,Integer&gt; letterTable;

Map&lt;Long,ArrayList&lt;String&gt;&gt; anagramTable;

&nbsp;

public Anagrams ()

private void buildLetterTable() &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; private void addWord(String s) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; private Long myHashCode(String s) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; public void processFile(String s) throws IOException &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; private ArrayList&lt;Map.Entry&lt;Long,ArrayList&lt;String&gt;&gt;&gt; getMaxEntries()

public static void main(String[] args)

&nbsp;

The constant primes should be initialized to an array consisting of the first 26 prime

numbers:

&nbsp;

<table width="529">
<tbody>
<tr>
<td width="529">{2,&nbsp; 3,&nbsp; 5,&nbsp; 7,&nbsp; 11,&nbsp; 13,&nbsp; 17,&nbsp; 19,&nbsp; 23,&nbsp; 29,&nbsp; 31,&nbsp; 37,&nbsp; 41,&nbsp; 43,&nbsp; 47,&nbsp; 53,&nbsp; 59,&nbsp; 61,</td>
</tr>
<tr>
<td width="529">67,&nbsp; 71,&nbsp; 73,&nbsp; 79,&nbsp; 83,&nbsp; 89,&nbsp; 97,&nbsp; 101};</td>
</tr>
</tbody>
</table>
&nbsp;

<sup>&nbsp;</sup>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 2

It will be used to set up the letterTable, a hash table that will associate each letter in the alphabet with a prime number. More precisely, it will associate “a” with 2, “b” with 3, “c” <sub>&nbsp;</sub>with 5, and so on.

The instance variable anagramTable will hold the main working hash table. Each entry in this hash table has the following format:

&nbsp;

Key (of type Long): the hash code of the word. It is important that this hash be the same for all anagrams of a word. The type Long is a 64-bit two’s complement integer. More details on how to produce this key will be given below.

&nbsp;

Value (of type ArrayList&lt;String&gt;): a list of the words seen up until now that have Key as hash code. Note that all the strings in this list are anagrams.

&nbsp;

We now describe each of the methods.

&nbsp;

<ul>
<li>Method processFile</li>
</ul>
&nbsp;

The main method is processFile which receives the name of a text file containing words, one per line, and builds the hash table anagramTable. For that it uses the addWord method. The implementation of this method is provided for you:

&nbsp;

<table width="529">
<tbody>
<tr>
<td width="529">Private void p r o c e s s F i l e ( String&nbsp; s )&nbsp; throws IOException&nbsp; { FileInputStream&nbsp; fstream&nbsp; =&nbsp; new&nbsp; FileInputStream( s );</td>
</tr>
<tr>
<td width="529">BufferedReader br = new BufferedReader ( new InputStreamReader( fstream )); String&nbsp; strLine ;</td>
</tr>
<tr>
<td width="529">while (( strLine&nbsp; =&nbsp; br. readLine ())&nbsp; !=&nbsp; null )&nbsp;&nbsp; { this.addWord ( strLine );</td>
</tr>
<tr>
<td width="529">}

br.close ();
</td>
</tr>
<tr>
<td width="529">}</td>
</tr>
</tbody>
</table>
&nbsp;

2

&nbsp;

4

&nbsp;

6

&nbsp;

8

&nbsp;

&nbsp;

&nbsp;

2

&nbsp;

<ul>
<li>Method buildLetterTable()</li>
</ul>
&nbsp;

This method should be invoked by the constructor for the class Anagrams and should build the hash table letterTable which consists of the following entries:

&nbsp;

<table width="528">
<tbody>
<tr>
<td width="528">{ a =2 , b =3 ,&nbsp; c =5 ,&nbsp; d =7 ,&nbsp; e =11 ,&nbsp; f =13 ,&nbsp; g =17 ,&nbsp; h =19 ,&nbsp; i =23 ,&nbsp; j =29 ,&nbsp; k =31 ,&nbsp; l =37 , m =41 , n =43 , o =47 ,&nbsp; p =53 ,&nbsp; q =59 ,&nbsp; r =61 ,&nbsp; s =67 ,&nbsp; t =71 ,&nbsp; u =73 ,&nbsp; v =79 ,&nbsp; w =83 , x =89 , y =97 , z =101}</td>
</tr>
</tbody>
</table>
&nbsp;

2

&nbsp;

This table is to be used in myHashCode, described next, for constructing the hash code of strings.

&nbsp;

5 Method myHashCode

&nbsp;

This method, given a string s, should compute its hash code. A requirement for myHashCode is that all the anagrams of a word should receive the same hash code. With that aim, you should resort to the fundamental theorem of arithmetic. The fundamental theorem of arithmetic), also called the unique factorization theorem or the unique-prime-factorization theorem, states that every integer greater than 0 either is prime itself or is the product of a unique combination of prime numbers, each to some power.

&nbsp;

As an example, the words “alerts” and “alters” should both receive the key 2.36204078E8, if we follow the encoding of letters given above.

&nbsp;

<h1>6 Method addWord</h1>
&nbsp;

This method should compute the hash code of the string s passed as argument, and should add this word to the hash table anagramTable.

&nbsp;

7 Method getMaxEntries

&nbsp;

This method should return the entries in the anagramTable that have the largest number of anagrams. It returns a list of them since there may be more than one list of anagrams with a maximal size. It will be called by the main method, whose code is described and supplied below.

&nbsp;

<h1>8 Method main</h1>
&nbsp;

The main method will read all the strings in a file, place them in the hash table of anagrams and then iterate over the hash table to report which words have the largest number of anagrams. Note that it refers to a file called words_alpha.txt. This file contains a

<sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sub>dictionary of words; instructions on how to obtain it are given below. Here is the code for the main method:

&nbsp;

&nbsp;

3

&nbsp;

&nbsp;

<table width="529">
<tbody>
<tr>
<td width="529">Public&nbsp; static&nbsp; void main ( String []&nbsp; args )&nbsp; {</td>
</tr>
<tr>
<td width="529">Anagrams&nbsp; a&nbsp; =&nbsp; new&nbsp; Anagrams ();

final&nbsp; long&nbsp; startTim e&nbsp; =&nbsp; System.nanoTime (); try&nbsp; {
</td>
</tr>
<tr>
<td width="529">a.processF i l e ( ” words_alpha.txt” ); }&nbsp; catch&nbsp; ( IOException e1 )&nbsp; {</td>
</tr>
<tr>
<td width="529">e1.printStackTrace ();

}
</td>
</tr>
<tr>
<td width="529">ArrayList &lt; Map.Entry &lt; Long , ArrayList &lt; String &gt;&gt;&gt; maxEntries = a.getMaxEntries(); final long&nbsp; estimatedTime = System.nanoTime () –&nbsp; startTime;</td>
</tr>
<tr>
<td width="529">final double&nbsp; seconds&nbsp; =&nbsp; (( double ) estimatedTime / 1000000000 ) ; System.out.println ( ” Time :&nbsp; “+&nbsp; seconds );</td>
</tr>
<tr>
<td width="529">System.out.println ( ” List&nbsp; of&nbsp; max&nbsp; anagrams :&nbsp; “+ maxEntries );

}
</td>
</tr>
</tbody>
</table>
&nbsp;

2

&nbsp;

4

&nbsp;

6

&nbsp;

8

&nbsp;

10

&nbsp;

12

&nbsp;

14

&nbsp;

Here is the expected output of your solution (the elapsed time may vary):

&nbsp;

<table width="529">
<tbody>
<tr>
<td width="529">Elapsed&nbsp; Time :&nbsp; 0.689135767

Key&nbsp; of&nbsp; max&nbsp; anagrams :&nbsp; 236204078
</td>
</tr>
<tr>
<td width="529">List&nbsp; of&nbsp; max&nbsp; anagrams :&nbsp; [ alerts ,&nbsp; alters ,&nbsp; artels ,&nbsp; estral ,&nbsp; laster ,&nbsp; lastre , rastle ,&nbsp; ratels ,&nbsp; relast ,&nbsp; resalt ,&nbsp; salter ,&nbsp; slater ,&nbsp; staler ,&nbsp; stelar ,&nbsp; talers ]</td>
</tr>
<tr>
<td width="529">Length&nbsp; of&nbsp; list&nbsp; of&nbsp; max&nbsp; anagrams :&nbsp; 15</td>
</tr>
</tbody>
</table>
1

&nbsp;

3

&nbsp;

5

&nbsp;

&nbsp;

<h1>9 Testing Your Solution</h1>
&nbsp;

<sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sub>In order to test your solution you are provided with a dictionary (words_alpha.txt) that has <sub>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; </sub>370099 words. You may download this file from this link:

&nbsp;

<a href="https://github.com/dwyl/english-words/blob/master/words_alpha.txt">https://github.com/dwyl/english</a><a href="https://github.com/dwyl/english-words/blob/master/words_alpha.txt">–</a><a href="https://github.com/dwyl/english-words/blob/master/words_alpha.txt">words/blob/master/words_alpha.txt</a>

&nbsp;

Place it in the folder where your project is located (the same folder where the bin and src folders are).

&nbsp;

&nbsp;
