# CBT585
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
//***FILE 585 is from Reed Petty, and contains a program called     *   FILE 585
//*           AWSSL, which takes disk datasets as input, and        *   FILE 585
//*           creates an SL virtual tape, in AWS format, as output. *   FILE 585
//*           Standard Labels are created for the "tape" files, by  *   FILE 585
//*           the AWSSL program.                                    *   FILE 585
//*                                                                 *   FILE 585
//*           This program creates AWS structures which contain     *   FILE 585
//*           one or more OS datasets of any record format          *   FILE 585
//*           (except spanned blocks), with or without standard     *   FILE 585
//*           labels, where the output AWS structure can also be    *   FILE 585
//*           of any record format (including spanned blocks).      *   FILE 585
//*                                                                 *   FILE 585
//*           This program will also retrieve datasets from an      *   FILE 585
//*           AWS structure of any record format (except spanned    *   FILE 585
//*           blocks).  The retrieved datasets may be reblocked     *   FILE 585
//*           if necessary.  If DCB attributes are omitted on the   *   FILE 585
//*           receiving dataset, and if standard labels are         *   FILE 585
//*           present within the AWS structure, then the DCB        *   FILE 585
//*           attributes of the receiving dataset will be           *   FILE 585
//*           defaulted to those within the HDR1 label.             *   FILE 585
//*                                                                 *   FILE 585
//*           AWS (acronym is unknown to me, someone please tell    *   FILE 585
//*           me!)  was widely used by the IBM P/390 product        *   FILE 585
//*           family to implement an entire tape volume as a byte   *   FILE 585
//*           stream contained within an OS/2 file.  As             *   FILE 585
//*           implementations of the System/360/370/zArch           *   FILE 585
//*           architecture families in software expanded (such as   *   FILE 585
//*           Hercules, Flex/ES, and others) the AWS presence       *   FILE 585
//*           expanded as well.                                     *   FILE 585
//*                                                                 *   FILE 585
//*           If you want to cut a real tape from the output of     *   FILE 585
//*           AWSSL, either you can create the output in FB-80      *   FILE 585
//*           format, and run the VTT2TAPE program from File 533.   *   FILE 585
//*                                                                 *   FILE 585
//*           If the output of AWSSL is VB, you can convert that    *   FILE 585
//*           file to AWS-format FB-80 using the VTT2CNVU program   *   FILE 585
//*           from File 533 of this tape.  That FB-80 AWS-format    *   FILE 585
//*           file can then be input into the VTT2TAPE program      *   FILE 585
//*           from File 533, and a real tape will be created.       *   FILE 585
//*                                                                 *   FILE 585
//*           email:  rhp@draper.net                                *   FILE 585
//*                                                                 *   FILE 585
```
