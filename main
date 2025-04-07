!pip install pymupdf pandas
import fitz

pdf_document = fitz.open("/wsh.pdf")


page1 = pdf_document[0]
page2 = pdf_document[1]
page3 = pdf_document[2]
page4 = pdf_document[3]
page5 = pdf_document[4]
page6 = pdf_document[5]
page7 = pdf_document[6]
page8 = pdf_document[7]
page9 = pdf_document[8]
page10 = pdf_document[9]
page11 = pdf_document[10]
page12 = pdf_document[11]

text1 = page1.get_text("words", sort=True)
text2 = page2.get_text("words", sort=True)
text3 = page3.get_text("words", sort=True)
text4 = page4.get_text("words", sort=True)
text5 = page5.get_text("words", sort=True)
text6 = page6.get_text("words", sort=True)
text7 = page7.get_text("words", sort=True)
text8 = page8.get_text("words", sort=True)
text9 = page9.get_text("words", sort=True)
text10 = page10.get_text("words", sort=True)
text11 = page11.get_text("words", sort=True)
text12 = page12.get_text("words", sort=True)



text = text1 + text2 + text3 + text4 + text5 + text6 + text7 + text8 + text9 + text10 + text11 + text12


for i, word in enumerate(text):

  txt = word[4]
  if txt == "Number:":
      contract = text[i+1][4]
  if txt == "CHK":
      total = text[i+1][4]
      print(contract + " " + total)



pdf_document.close()
