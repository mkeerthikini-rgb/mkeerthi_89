mport nltk
try:
    nltk.data.find('corpora/brown')
except LookupError:
    nltk.download('brown')
try:
    nltk.data.find('taggers/universal_tagset')
except LookupError:
    nltk.download('universal_tagset')

print("NLTK and required datasets (brown, universal_tagset) are ready.")# mkeerthi_89
