For each topic (e.g. "pens") there are 6 different items in the dataframe. They are listed in the following dictionary:

    questions = {"pens":["Q17", "Q18","Q211","Q215","FL_174_DO_PencilsAgree", "FL_174_DO_PencilsDisagree"],
                 "chalk":["Q28","Q29","Q201","Q205","FL_181_DO_ChalkAgree","FL_181_DO_ChalkDisagree"],
                "p":["QID86","QID87","Q187","Q189","FL_182_DO_PAgree","FL_182_DO_PDisagree"],
                 "cinder":["Q32","Q33","Q184","Q185","FL_183_DO_CinderAgree","FL_183_DO_CinderDisagree"],
                "circle":["Q260","Q262","Q261.0","Q262.0","FL_201_DO_Circagree","FL_201_DO_Circdisagree"],
                 "table":["Q264.0","Q266","Q265.0","Q266.0","FL_200_DO_TableAgree","FL_200_DO_Tabledisagree"]}

For each topic:
- The first item is the pre-exposure question (e.g. "Pencils are charming" - Agree or Disagree)
- The second is the certainty of the pre-exposure question (i.e. "On a scale of 1-10, please rate how certain you are of this view")
- the third is the post-exposure question (e.g. "Pencils are charming" - Agree or Disagree)
- The fourth is the certainty of the pre-exposure question (i.e. "On a scale of 1-10, please rate how certain you are of this view")
- The last two are binary variable that represent if the bogus participant (i.e. the exposure) agrees or disagrees with the statement.



