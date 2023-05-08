# Lab Report 3

**Command 1, Example 1**
`less -N 911report/chapter-13.1.txt` 



**Command 1, Example 2**
`
less -N biomed/cc2190.txt 
`



The command line option with `-N` displays line numbers for the contents of a file. This can be useful in many ways. First, it can allow you to reference specific line numbers in the file, making it easier to identify, locate, and look at the information you want. It can also allow you to navigate the file much faster and easier, especially for large files, since you can look up and read a specific line in a file.

Source: https://linuxize.com/post/less-command-in-linux/

---

**Command 2, Example 1**

`yotokim@Yotos-MacBook-Pro-2 technical % less -X 911report/chapter-12.txt`

    
       
            WHAT TO DO? A GLOBAL STRATEGY
            REFLECTING ON A GENERATIONAL CHALLENGE
            Three years after 9/11, Americans are still thinking and talking about how to protect
                our nation in this new era. The national debate continues. Countering terrorism has
                become, beyond any doubt, the top national security priority for the United States.
                This shift has occurred with the full support of the Congress, both major political
                parties, the media, and the American people.
            The nation has committed enormous resources to national security and to countering
                terrorism. Between fiscal year 2001, the last budget adopted before 9/11, and the
                present fiscal year 2004, total federal spending on defense (including expenditures
                on both Iraq and Afghanistan), homeland security, and international affairs rose
                more than 50 percent, from $354 billion to about $547 billion. The United States has
                not experienced such a rapid surge in national security spending since the Korean
                    War.
            
            This pattern has occurred before in American history. The United States faces a
                sudden crisis and summons a tremendous exertion of national energy. Then, as that
                surge transforms the landscape, comes a time for reflection and reevaluation. Some
                programs and even agencies are discarded; others are invented or redesigned. Private
                firms and engaged citizens redefine their relationships with government, working
                through the processes of the American republic.
            Now is the time for that reflection and reevaluation. The United States should
                consider what to do-the shape and objectives of a strategy. Americans should also
                consider how to do it-organizing their government in a different way. Defining the
                Threat In the post-9/11 world, threats are defined more by the fault lines within
                societies than by the territorial boundaries between them. From terrorism to global
                disease or environmental degradation, the challenges have become transnational
                rather than international. That is the defining quality of world politics in the
                twenty-first century.
            National security used to be considered by studying foreign frontiers, weighing
                opposing groups of states, and measuring industrial might. To be dangerous, an enemy
                had to muster large armies. Threats emerged slowly, often visibly, as weapons were
                forged, armies conscripted, and units trained and moved into place. Because large
                states were more powerful, they also had more to lose. They could be deterred.
            Now threats can emerge quickly. An organization like al Qaeda, headquartered in a
                country on the other side of the earth, in a region so poor that electricity or
                telephones were scarce, could nonetheless scheme to wield weapons of unprecedented
                destructive power in the largest cities of the United States. In this sense, 9/11
                has taught us that terrorism against American interests "over there" should be
                regarded just as we regard terrorism against America "over here." In this same
                sense, the American homeland is the planet. But the enemy is not just "terrorism,"
                some generic evil.
            
            This vagueness blurs the strategy. The catastrophic threat at this moment in history
                is more specific. It is the threat posed by Islamist terrorism-especially the al
                Qaeda network, its affiliates, and its ideology.
            
            As we mentioned in chapter 2, Usama Bin Ladin and other Islamist terrorist leaders
                draw on a long tradition of extreme intolerance within one stream of Islam (a
                minority tradition), from at least Ibn Taimiyyah, through the founders of Wahhabism,
                through the Muslim Brotherhood, to Sayyid Qutb. That stream is motivated by religion
                and does not distinguish politics from religion, thus distorting both. It is further
                fed by grievances stressed by Bin Ladin and widely felt throughout the Muslim


In the above code, I ran `less` with  `-X` on the `911/report/chapter-12.txt` file. As usual, it printed out the contents of the file, one page at a time like the usual function of just `less`. But with the `-X`, it actually leaves the file contents on the screen even when you exist `less`. Below the second example, I wrote about why the command is useful.

**Command 2, Example 2**

`yotokim@Yotos-MacBook-Pro-2 technical % less -X biomed/rr74.txt` 

        Introduction
        NO, which may be synthesized by any of the three
        isoforms of NOS, is a vasodilator of the pulmonary
        circulation in many mammals. NO has been proposed as a
        modulator of vascular tone and structure in the pulmonary
        circulation, and previous studies using NOS inhibitors [ 1,
        2] suggested that inhibition of NO increases acute hypoxic
        pulmonary vasoconstriction. Chronic NOS inhibition did not
        lead to development of pulmonary hypertension [ 3],
        however, possibly because of a decrease in cardiac output.
        These discrepancies have been addressed in recent studies
        using mice that are deficient in NOS isoforms.
        Three isoforms of NOS are found in the lung. The
        principle isoform that is found in the pulmonary
        vasculature is eNOS [ 4]. iNOS is expressed in airway
        epithelium, and airway and vascular smooth muscle [ 5, 6],
        whereas nNOS is expressed in the bronchial epithelium and
        lung nervous tissue [ 4, 5, 7, 8]. Thus, all three NOS
        isoforms could contribute to modulation of pulmonary
        vascular tone. Studies using knockout mice for each of
        these isoforms [ 9, 10, 11, 12] suggest that eNOS-derived
        NO is important in modulating basal pulmonary vascular
        tone, as well as in attenuating the development of
        pulmonary hypertension.
        Severe sustained hypoxia causes pulmonary hypertension
        in many animals. Upregulation of all three NOS isoforms
        following severe hypoxia has been reported in rats [ 4, 13,
        14, 15, 16]. Less is certain about the expression of NOS in
        the murine lung following hypoxia, with previous reports [
        17, 18] suggesting an increase in lung eNOS and iNOS
        levels. We therefore hypothesized that NOS isoforms are
        upregulated following hypoxia and that this may account for
        the increased susceptibility to hypoxic pulmonary
        hypertension in mice that lack eNOS [ 9, 12]. In the
        present study we exposed wild-type mice to severe hypobaric
        hypoxia from birth and measured NOS mRNA and protein
        levels. We then compared the findings with localization of
        NOS protein in the lung as assessed using
        immunohistochemistry.
      
      
        Materials and methods
        
          Mice
          We studied F1-generation SV129 (Taconic, Germantown,
          NY, USA) and C57BL/6 (Jackson Laboratories, Bar Harbor,
          ME, USA) mice at age 6 weeks.
        
        
          Exposure environments
          Within 24-36 h of birth, pups and dam were placed in
          ambient conditions, hypobaric hypoxia (simulating an

In this second example, `less` with  `-X` was used on the `biomed/rr74.txt` file, printing out the first page of the file contents and leaving the file contents on the screen after exiting `less`.When using `less`, the file contents are usually cleared from the screen. However, the `-X` option allows the contents to leave the contents on screen. In the example above, it prints out the contents of the `biomed/rr74.txt` file and leaves it there. This is useful as the file may have important information that you want to refer to or view easily later. It can also help you keep track of which file you were viewing at which time since the file contents will remain even after you exist `less`.

Source: https://linuxize.com/post/less-command-in-linux/

---

**Command 3, Example 1**
`less -pAmerica 911report/chapter-1.txt`

Output:

**Command 3, Example 2**
`less -pRNA biomed/cc2172.txt`

Output:


Source: https://phoenixnap.com/kb/less-command-in-linux

---

**Command 4, Example 1**
`less -m 911report/chapter-2.txt`


**Command 4, Example 2**
`
