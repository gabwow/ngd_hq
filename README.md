ngd_hq
======

Notes for the NextGen Data Hackathon at MSKCC

**What**: A two-day hackathon around the data generated as intermediate and final stages of next-generation sequencing

**When**: August 29th, 12pm- August 30th, 8pm

**Where**: Memorial Sloan Kettering Zuckerman Building
417 East 68th Street, between 1st Ave and York

**Why**: The core technologies behind next-generation sequencing are now somewhat stable, but there is still room for improvement. There are efforts (e.g. Hadoop for bioinformatics) for large-scale transformations in data handling, and there are still many smaller problems that crop up in real world analysis (e.g. there really is no common vcf). This hackathon will look at analysis bottlenecks caused by data representation, and work on cool applications to solve them.

This hackathon will feature:

* A chance to network and share ideas
* Brief introductions to emerging data solutions in cancer genomics
* A jaw-droppingly minor cash prize for best application and free food

**Who**: We are looking for:

* Programmers
* Large-scale-data masterminds
* Researchers familiar with next-gen data

## FAQ:

*Do I need to know anyone there?* Nope. We'll briefly present different ideas and then form groups based on mutual interests. If there is someone that you already know you do want to work with, that's great too.

*Do I need to be there for all of this?*  No. This is as intense as you choose to make it. Ideally you'd be there at noon on Friday, but if you can't get there by then, we ask for you to be there at 6pm on Friday, just so everybody can get into a group. We also are strongly encouraging a 2pm partnered code-review. Ideally, this would be done in person, but if people want to do it through something like google hangout, that's fine too. 

That said, if you want to go all out, dinner and breakfast will be provided. 

*What programming language will things be written in?* This event is language agnostic. That said, some of the APIs are not. For example, NVBio relies on CUDA. For the Saturday partnered code review, hopefully we can work out pairings that make sense, but don't let this concern be a deal breaker.

## APIs (suggestions welcome):
* [MongoDB](http://docs.mongodb.org/manual/)
* [SeqPig](http://seqpig.sourceforge.net/)
* [NVBio](https://github.com/NVlabs/nvbio)
* [Adam](https://github.com/massie/adam)

## Schedule
**Friday 12 pm**, 11th floor conference room (Z1170):

Brief discussion of data issues and people propose projects

**Friday 6pm**, 11th floor conference room (Z1170):

New arrivals catch up on what’s going on

**Friday 7:30 pm**, 4th floor conference room (Z466):

Dinner

**Saturday 12am**, 4th floor conference room (Z466):

Snacks

**Saturday 8am**, 4th floor conference room (Z466):

Breakfast

(lunch not provided)

**Saturday 2pm**, 4th floor and 11th floor conference room:

Partnered code review

Saturday 7pm, 11 floor conference room (Z1170):

Final code submission and project demos


**What you need**:

A computer, a power cord, and a vague idea about the sort of problem you want to work on. For demos, we have several Mac adapters for projectors, but given Apple's vast plug options, you may want to bring your own if you want to assure projector usage.

**What you may want**:

You might have to rely on MSKCC's public wifi, which can be slow, particularly during peak hours of operation. You can set yourself up for success by downloading any data and programs you think you'll need before the event. If you want to be a real time-management superstar, you can install and verify all the packages you'll need are running correctly before the event. If you think you'll want to work on cluster, and you don't have ready access to one, or lack the admin powers you'll need, you might want to set-up an Amazon Web Service. If you want to try and sort everything out during the hackathon, that's fine too.

Since you may end up working with people who don’t have permission to view the same data that you do, you might want to grab some public data. There 1000 Genomes project has some smallish .bam, .fastq and .vcf files that you can grab.

 ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/

To get the bams, cd data/HG00096/alignment

To get the fastqs, cd data/HG00096/sequence_read

To get the VCFs:

ftp://ftp-trace.ncbi.nih.gov/1000genomes/ftp/release/20101123/interim_phase1_release/


Apart from the technical side of things, you may want to bring some personal items (e.g. toothbrush, change of clothes) if you plan on working overnight (there will be a dedicated space for power napping). While dinner, snacks, and breakfast will be provided, if you have serious eating restrictions, you should bring your own food. 

## Code of Conduct
We want this event to be enjoyable to everyone, and ask for everybody to treat each other, and the work spaces, respectfully. Don't let your pursuit of fun and learning ruin someone else's.

