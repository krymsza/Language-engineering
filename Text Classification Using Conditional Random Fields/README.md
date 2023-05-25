#Text Classification Using Conditional Random Fields


best results were achieved with features :
      'word[-2:]': word[-2:],
        'word[:2]': word[:2],
        'word[:3]': word[:3],
        'word[-3:]': word[-3:],

wynik na danych testowych(testing data results:)


                        precision    recall  f1-score   support

                date      0.899     0.894     0.897      7502
            geogName      0.638     0.458     0.533      5329
            persName      0.882     0.552     0.679      1363
    persName_addName      0.441     0.043     0.078       955
    persName_forename     0.857     0.766     0.809     11037
    persName_surname      0.802     0.879     0.839     10814
                time      0.806     0.636     0.711      1397
           placeName      0.883     0.449     0.595       303
    placeName_bloc        0.152     0.041     0.065       121
    placeName_country     0.884     0.820     0.851      6462
    placeName_district    0.339     0.064     0.107       330
    placeName_region      0.703     0.250     0.369       909
    placeName_settlement  0.797     0.636     0.707      7312
             orgName      0.779     0.650     0.708     16635

           micro avg      0.814     0.709     0.758     70469
           macro avg      0.704     0.510     0.568     70469
        weighted avg      0.803     0.709     0.746     70469
        weighted avg      0.803     0.709     0.746     70469
