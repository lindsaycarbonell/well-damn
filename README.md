# When You Give a Girl a Dam Database...
I've got lots of questions about N.C. dams (not wells, unfortunately) and I'm finding lots of answers.

## Research so far: 

[All of the notes about dams](https://docs.google.com/document/d/190o0ekqcoiMme09ZGevruzrCSB6GjPkvZzqWvviUim4/edit?usp=sharing)

[Second post draft so far](https://docs.google.com/document/d/1bfJufvsWdtCcLkuh86kKI1o-lAeWebWVso7MEaYCjY0/edit?usp=sharing)

## Deliverables
- [Dam That Hasn't Been Inspected in Over 30 Years Also Doesn't Exist, Probably](http://carolinadatadesk.org/dam-that-hasnt-been-inspected-in-over-30-years-also-doesnt-exist-probably/)

## Things you can expect from me about dams: 

- A blog post about how I'm determining the best ways to find the answer to life's burning question: "How likely is it that the dam(s) near me will affect my life?"
- Possibly a web app that crowdsources finding dams that have been breached (unless there's already a field for that in the database, which will make me embarassed but also, secretly, I will still want to make a Find Dams Near You adventure app)
- A...*sigh*...fact sheet about dams.
- And visuals!! When I find things that can be best told visually. Like on maps. Probably.

## Other Burning Q's

- What do the data look like with Woodlake Dam compared to Oroville Dam? (Maybe not comparable b/c of size)
- Hurricane preparedness and dams -> which dams failed during Hurricane Matthew, which dams failed during other hurricanes? Correlation b/w inspection tardiness and dam failure during dams, or is it mostly random?

## Visual Ideas

- It's pretty much necessary that I make an exploratory database with a map element, probably very similar to the Washington Post's [structurally deficient dams graphic](https://www.washingtonpost.com/graphics/national/structurally-deficient-bridges/?tid=sm_tw#37045).
  - (I started on the map, prototype can be seen so far by running ``python -m SimpleHTTPServer 8000`` on this repository)
- Timeline of events with Woodlake Dam, and comparing that timeline to dams in the database that are going in a similar direction.

## Data I need
- Historical records of when dams have been inspected (likely in state's database)
- If a dam has been breached and the condition of the dam
  - this is apparently part of the DEQ database, I made a call to figure out how to request the updated db
