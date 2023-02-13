Git  && Github

 1. git init ==> This folder is use git to noti 
		(Initialized empty Git repository in D:/Web learning/Git/.git/)

 2. git status ==> file တွေ ပြောင်းလဲမှု ကို ကြည့်ခြင်း 

 3. git add .
	(git ထဲကို file တွေ ထည့်မယ်လို့ ကြေငြာခြင်း )

 4. git commit -m "ပေးချင်တဲ့ အမည်"

 5. git remote add [github link nickname][github link]
	( local code နဲ့ github ကိုချိတ်ခြင်း)
	eg/ git remote add origin https://github.com/htetthinzarmoe123/example.git

 6. git branch -M [တင်ချင်တဲ့ branch-name]
	(local branch name နဲ့ github branch name က တူရမယ် )
	(တင်ချင်တဲ့ branch ကိုသွားခြင်း ) 
 	eg/ git branch -M main

 7. git push -u [romote-name][branch-name]
	(github ပေါာ တင်ခြင်း)
	eg/ git push -u origin main

...............................................................................................................................

 git remote -v  ( remote ကိုပြန်ကြည့်ခြင်း ) 
 
 git remote remove [ဖျက်ချင်တဲ့ remote-name ]

 git branch -a (လက်ရှိ‌ေရာက်နေတဲ့ branch-name ကိုကြည့်ခြင်း)

 git switch [branch-name/branch-id] (or) git checkout [branch-name/branch-id] (branch ချိန်းခြင်း )

 git log --outline 

 git merge [ပေါင်းထည့် ချင်တဲ့ branch-name ] (branch တွေပေါင်းခြင်း ) 
	ပေါင်းခံရမယ့် branch ကို git checkout နဲ့ အရင် သွားရမယ်


	
 