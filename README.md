Download Link: https://assignmentchef.com/product/solved-cs240-introduction-to-computing-iii-mp04-linked-list
<br>



<strong>Objectives</strong>

&#x25aa; To use a linked list to process state data

&#x25aa; To read from a file

&#x25aa; To use pointers and dynamic memory management

<strong>Project setup</strong>

Create the project <strong>mp04.&lt;FirstLast&gt;</strong>. Replace FirstLast with your name and do not include the &lt;&gt; brackets. For instance, <strong>mp04.SocratisTornaritis</strong>.

Add the provided files to your project:

main.cpp

States.hpp

LinkedList.hpp

The folder <strong>mp04.Firstlast</strong> containing just the source file(s) and text file(s), is the one that you must zip and upload. Do not upload any IDE specific files.

Refer to the appropriate “how to” tutorial notes available on the course website, for instructions on how to create a project and manage its files.

<strong>Problem description:</strong>

A text file, <em>states.txt</em>, is provided with state information. Your program will read the state data into seven instances of the <em>States</em> class. Each instance will correspond to the data sorted by one of the seven fields (<strong>abbreviation</strong> to <strong>orderInducted</strong>).

The data thus will be read in seven times, once for each instance. The instances will then be sorted by their respective field, and finally added to a <em>LinkedList</em> instance. This <em>LinkedList</em> instance will contain <em>States</em> nodes.

The driver will offer the end user the option to list the data in one of the seven sort fields. Refer to the screen cast below.

<strong>Program requirements:</strong>

<ul>

 <li><strong>Code the implementation of the </strong><strong><em>States</em> </strong></li>

</ul>

Refer to the imbedded comments in the <em>States.h</em> file for details.

<ul>

 <li><strong>Complete the implementation of the partial main.cpp</strong></li>

</ul>

Implement the TODOs inside the provided <em>main.cpp</em> file.

As you write your programs from here on out, documentation will be desirable and an essential part of your code. Add the following section to each of your programs to identify relevant information to anyone reading your code. The sample below is what I used for Main.java, so make the appropriate changes to reflect your current/accurate information. This is just a sample, so feel free to add to it if you want, but do not remove anything.

/*    File: &lt;filename&gt;

<ul>

 <li>Name: &lt;your name&gt;</li>

 <li>Revised: &lt;date authored&gt;</li>

 <li>Course: CS240 – Introduction to Computing III</li>

</ul>

*

<ul>

 <li>Desc: &lt;program description&gt;</li>

</ul>

*/

<table width="624">

 <tbody>

  <tr>

   <td width="624">Select sort field [A]bbreviation, [N]ame, [C]apital, [P]opulation, A[r]ea, [Y]ear Inducted, [O]rder Inducted, [Q]uit: aAbbreviation   Name             Capital            Population       Area   Year Inducted   Order Inducted———————————————————————————————————AK             Alaska           Juneau                 710231     663267            1959               49AL             Alabama          Montgomery            4779736      52419            1819               22AR             Arkansas         Little Rock           2915918      53179            1836               25AZ             Arizona          Phoenix               6392017     113998            1912               48CA             California       Sacramento           37253956     163696            1850               31CO             Colorado         Denver                5029196     104094            1876               38CT             Connecticut      Hartford              3574097       5543            1788                5DE             Delaware         Dover                  897937       2489            1787                1FL             Florida          Tallahassee          18801310      65755            1845               27GA             Georgia          Atlanta               9687653      59425            1788                4HI             Hawaii           Honolulu              1360301      10931            1959               50IA             Iowa             Des Moines            3090416      56273            1846               29ID             Idaho            Boise                 1567582      83570            1890               43IL             Illinois         Springfield          12830632      57914            1818               21IN             Indiana          Indianapolis          6483802      36417            1816               19KS             Kansas           Topeka                2893857      82278            1861               34KY             Kentucky         Frankfort             4395295      40411            1792               15LA             Louisiana        Baton Rouge           4625470      51988            1812               18MA             Massachusetts    Boston                6692824      10554            1788                6MD             Maryland         Annapolis             5928814      12406            1788                7ME             Maine            Augusta               1328302      35384            1820               23MI             Michigan         Lansing               9895622      96713            1837               26MN             Minnesota        St. Paul              5420380      86935            1858               32MO             Missouri         Jefferson City        6044171      69702            1821               24MS             Mississippi      Jackson               2991207      48432            1817               20MT             Montana          Helena                1015165     147039            1889               41NC             North Carolina   Raleigh               9848060      53819            1789               12ND             North Dakota     Bismark                723393      53819            1889               39NE             Nebraska         Lincoln               1868516      77349            1867               37NH             New Hampshire    Concord               1323459       9348            1788                9NJ             New Jersey       Trenton               8899339       8723            1787                3NM             New Mexico       Santa Fe              2085287     121590            1912               47NV             Nevada           Carson City           2790136     110572            1864               36NY             New York         Albany               19615127      54555            1788               11OH             Ohio             Columbus             11570808      44825            1803               17OK             Oklahoma         Oklahoma City         3850568      69899            1907               46OR             Oregon           Salem                 3930065      98379            1859               33PA             Pennsylvania     Harrisburg           12773801      46055            1787                2RI             Rhode Island     Providence            1051511       1545            1790               13SC             South Carolina   Columbia              4774839      32021            1788                8SD             South Dakota     Pierre                 844877      77116            1889               40TN             Tennessee        Nashville             6495978      42144            1796               16TX             Texas            Austin               26448193     268597            1845               28UT             Utah             Salt Lake City        2900872      84897            1896               45VA             Virginia         Richmond              8260405      42775            1788               10VT             Vermont          Montpelier             626630       9616            1791               14WA             Washington       Olympia               6971406      71298            1889               42WI             Wisconsin        Madison               5742713      65496            1848               30WV             West Virginia    Charleston            1852996      24230            1863               35WY             Wyoming          Cheyenne               582658      97812            1890               44 Select sort field [A]bbreviation, [N]ame, [C]apital, [P]opulation, A[r]ea, [Y]ear Inducted, [O]rder Inducted, [Q]uit:</td>

  </tr>

 </tbody>

</table>





