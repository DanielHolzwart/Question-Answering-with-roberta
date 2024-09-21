# Question-Answering-with-roberta

We will be looking at a CV example pdf containing 8 pages. Included is a small introduction what CVs are about and then example CVs of two fictional characters. We are going to use the roberta model trained on SQuAD2 for queston answering to ask specific questions about this Juan Garcia. As the size of a 8 page document is higher than roberta's allowed input size, we are going to do some prepocession of data and split the data into chunk with strides. Then roberta is going to evaluate the question on each of such chunks.
