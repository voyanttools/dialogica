# Stopword and White List Help File

Voyants uses a Stopword list in most tools to control what words you see. The list of words in the Stopword list are words that appear frequently like "the" and "and", but which we often are not interested in (unless studying such function words.) By default it is set to Auto-detect which detects the language you are using and, if we have a stopword list in that language, uses it. That means that in the Cirrus word cloud, for example, you don't see the most common words that are in the list. To choose or edit the list used do the following:

<img src="/terms.options.jpg" alt="Options Panel" width="400">


1. Select the **Options panel** in the tool you want to affect. (You can set them globally too!)
2. Click on the menu where it says "Auto-detect". That will give you choices if you want to force Voyant to use a language. Alternatively you can enter the ID of an edited stopword list right in the field instead of "Auto-detect".
3. If you want to Edit the list then click the **Edit** button next to the field/menu. That will open this **Edit Stoplist** panel:

<img src="/stopword.edit.jpg" alt="Options Panel" width="300">

4. To edit the list, just delete words or type them in. Then press **Save**.
5. Note that you will now see a custom ID for the Stopword list in the Options panel. If you want to reuse this edited list in another Voyant session you should click on the ID and copy it so you can save it somewhere.

<img src="/keyword.id.jpg" alt="Options Panel" width="400">

**Note:** When you choose or edit the Stopword list you can also select to **apply globally** your edits. That means that the edited list is used in any tool where it makes sense. In some cases you may just want to keep the edited list local. 

## White List

Voyant also allows you to specify **White List** of words which is the opposite of a stopword list. A White List is a list of words which you want to limit Voyant's visualization to. If you edit and save a White List then visualizations like the Cirrus word cloud will only show words on that list and no others. This can be a way of producing a visualization of specific words. Of course, other settings may mean that words in your White List don't show up. For example, if you limit the number of terms displayed to fewer than you have in your list.

## Help for Stopwords

More help is available [here for Stopwords](https://voyant-tools.org/docs/#!/guide/stopwords).

----

[Dialogica Home](/index.md) | [Voyant Help Files](/voyanthelp.md)

----

&copy; Stéfan Sinclair & Geoffrey Rockwell

All materials on this site shared under a [Creative Commons By Attribution license](https://creativecommons.org/licenses/by/4.0/).
