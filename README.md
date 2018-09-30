# Rnet Dataset

## 格式範例

參考 sister_dataset.json

## TODO

1. 先改改看 sister_dataset.json 的 position， 算斷詞後的 position
2. 尚未斷詞
3. 未改成繁體中文
4. 断詞後，找 position 順便觀察有無斷詞失敗的詞，並記錄下來當成字典且修改，再以此字典再斷詞一份新的檔案看看是否正確。

## Training Data Set

Our training data set are made up of the fallowing:

- sister: 323 stories, 1001 qas
- cmcr2018_train: 2403 stories, 10142 qas
- cmcr2018_dev: 848 stories, 3219 qas

## Test Data set

Our testing data set is the fallowing:

- cmcr2018_trial
