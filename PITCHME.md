---?image=assets/img/code.jpg&opacity=60&position=left&size=45% 100%

@snap[east span-50 text-center]
## R **seminar**
### Tue Hellstern
@snapend

---

### Tidsplan
@ul[](false)
- Velkommen kl. 17:00
- Sandwich Kl. 18:15 - 18:45
- Kaffe/The/Kage Kl. 20:00 - 20:15
- Spørgsmål Kl. 21:00
- Slut Kl. 21:30 
@ulend

---

### Agenda
@ul[](false)
- 
- Kontrol struktur if-else // switch
- Loops i R
- 
-  
@ulend

---

@snap[north-east span-100 text-pink text-06]
if-else
@snapend

```r zoom-18
if(logical condition evaluating to either TRUE or FALSE)
{
First set consisting of one or more R expressions
else
}
{
Second set consisting of one or more R expressions
}
```

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend

---
@snap[north-east span-100 text-pink text-06]
Let your code do the talking!
@snapend

```sql zoom-18
CREATE TABLE "topic" (
    "id" serial NOT NULL PRIMARY KEY,
    "forum_id" integer NOT NULL,
    "subject" varchar(255) NOT NULL
);
ALTER TABLE "topic"
ADD CONSTRAINT forum_id
FOREIGN KEY ("forum_id")
REFERENCES "forum" ("id");
```

@snap[south span-100 text-gray text-08]
@[1-5](You can step-and-ZOOM into fenced-code blocks, source files, and Github GIST.)
@[6,7, zoom-13](Using GitPitch live code presenting with optional annotations.)
@[8-9, zoom-12](This means no more switching between your slide deck and IDE on stage.)
@snapend


---?image=assets/img/code.jpg&opacity=60&position=left&size=45% 100%

@snap[east span-50 text-center]
## R **seminar**
### Tue Hellstern
@snapend


