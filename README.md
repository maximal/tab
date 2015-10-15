Sorry guys, but I have to.

 * * *

Tabs advantages:

 * Tabs are _designed to be_ an indentation character. They are _semantically correct_.
 * Tabs can be configured to have different width.
 * Tabs keep source code size _meaningful_, not exaggerating characters count by 4 times with meaningless whitespace characters. With tabs, 5k file, say, is 4k source and 1k whitespace. With spaces, 5k file is 1-2 source and 4-3 k whitespace.
 * Many IDEs do the smart-tabbing _automatically_, making this approach transparent and clean.

Spaces advantages:

 * Code looks the same in different editors.
 * Any more? (Disregarding that they are standard, only logical and usability points).

Spaces has become a standard, yes. But that was strictly because people were unable to use tabs properly. That was 30-, 20-, 10-years-ago problem. But why are people unable to use tabs now, when IDEs are mighty?

The less we use tabs, the less chances they have to become standard. People now are just afraid to use them. It means that standard needs to be reviewed.

Tabs-vs-spaces is not a holy war, it’s a confrontation between logic/reason and majority.

I just want reason to become majority and standard.


 * * *


Let’s be logical.

The most reasonable indentation style out there is SmartTabs: indentation with tabs, alignment with spaces.
It is useful, state-of-the-art and logically right: you can change tab size and alignment doesn’t break anywhere.
Many modern IDEs and editors support this approach.

http://www.emacswiki.org/SmartTabs

But now, _vast majority_ of people are _afraid_ to use smart tabs even though it is very reasonable approach. Just because spaces are PSR-2 standard.

For example, see discussion of Yii2 framework, which switched to spaces recently:
yiisoft/yii2#2747.

I agree, that framework in any given language, probably, should use current standard for this language.
But why does unreasonable standard remain real then?

Spaces-only indentation is relic of the past, when people didn’t use (or didn’t know about) smart-tabs indentation.
Now all people follow space-standard just to follow it, without any semantic reason.
