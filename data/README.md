# Data Description: College Data

We used the `tuition_cost` and `salary_potential` datasets available at 
https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-03-10/readme.md

This dataset includes information of colleges all around the United States regarding Tuition, Career Payment, and Diversity. 

The data fields included are: name (of school), state, state code (two letter abbreviation of state), type (Public, Private, For Profit, etc), degree length, room and board price, in state tuition, in state cost total price, out of state tuition, out of state cost total price, rank, early career pay (less than ), mid career pay ( ), percentage of alumni who want to make the world better, and percentage of univeristy in STEM degrees  

# Data Dictionary

|Field Name | Description | Data Type | Data Size|
|:----------|:---------------|:---------|:------------|
|name|Institution Name|factor|486|
|state_code|State Abbreviation|factor|486|
|make_world_better_percentPercent of alumni who think they are making the world a better place|integer|486|
|room_and_board|Room and board in USD|integer|486|
|ln_room_and_board|Natural Log of Room and board in U$D|double|486|
|early_career_pay|Estimated early career pay in USD|int|486|
|ln_early_career_pay|Natural log of estimated early career pay in USD|double|486|
|mid_career_pay|Estimated mid career pay in USD|int|486|
|ln_mid_career_pay|Natural log of estimated mid career pay in USD|double|486|
|total_enrollment|Total enrollment of students|double|486|
|ln_total_enrollment|Natural Log of Total enrollment of students|double|486|
|out_of_state_tuition|Tuition for out-of-state residents in USD|integer|486|
|ln_out_of_state_tuition|Natural Log of Tuition for out-of-state residents in USD|double|486|
|in_of_state_tuition|Tuition for in-of-state residents in USD|integer|486|
|ln_in_of_state_tuition|Natural Log of Tuition for in-of-state residents in USD|double|486|
|stem_percent|Percent of student body in STEM|double|486|
|private|Type: 0 for Public, 1 for Private|integer|486|
|asian_ratio|Percentage of Asian Students|double|486|
|black_ratio|Percentage of Black Students|double|486|
|minority_ratio|Percentage of all Minorities Combined|double|486|
|hispanic_ratio|Percentage of Hispanic Students|double|486|
|women_ratio|Percentage of Women Students|double|486|
|tuition_ratio|Out-of-State Tuition and In-State Tuition Ratio|double|486|
