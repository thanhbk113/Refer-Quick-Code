## <strong id="up">Refer-Quick-Code</strong>

#React
<br/>
<ul>
<li>
<a href="#wait-time">Wait time await (ex:2000ms)</a>
</li>
<li>
<a href="#prop-style">Prop styled component mui typescript</a>
</li>
 <li>
<a href="#mutiple-tenary">Multiple tenary operator</a>
</li>
<li>
<a href="#get-key-string-array">Get value by key string array</a>
</li>
<li>
<a href="#handlePath">Solve path react router v6</a>
</li>
<li>
<a href="#classCombine">Class combine type and function</a>
</li>
<li>
<a href="#breakline">Break line when text too long</a>
</li>
<li>
<a href="#toggle">Toggle any position child of parent click</a>
</li>
</ul>
#Golang
<br/>
<ul>
<li>
<a href="#typeTGo">Type T in Go</a>
</ul>
<br/>
#Next
<ul>
</li>
<li>
<a href="#quill-next">Import react quill in next js ssr=false</a>
</li>
</ul>
#Git Tips
<br/>
<ul>
<li>
<a href="#stash">Git stash before pull save your code</a>
</ul>
<br/>
<h2 id="wait-time">Wait time await (ex:2000ms)</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/206338167-ed3094a5-64e5-4164-b576-fcadbafea27c.png" alt="image" width={200} height={200}/>
<h2 id="prop-style">Prop styled component mui typescript</h2>
 <br/>
<img src="https://user-images.githubusercontent.com/97892253/197729845-0f7b4a51-12af-4b4c-86ec-2ac2bf68c68b.png" alt="image" width={200} height={200}/>
<br/>
<h2 id="mutiple-tenary">Multiple tenary operator</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/199876311-5402052d-c307-4ae3-8d62-09778317d83d.png" alt="image" width={200} height={200}/>
<br/>
<h2 id="get-key-string-array">Get value by key string array</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/199945390-147ca8c7-9eea-45c8-8f64-595bd0a4a7a9.png" alt="image" width={200} height={200}/>
<br/>
<h2 id="handlePath">Solve path react router v6</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/200101232-d2940bbe-1fff-441d-8b28-218d4b7ce9c8.png" alt="image" width={200} height={200}/>
<h2 id="classCombine">Class combine type and function</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/202183617-6a8859ff-c760-4f08-9f13-ca50190c0b36.png" alt="image" width={200} height={200}/>
<br/>
<h2 id="breakline">Break line when text too long</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/208369837-93058a9b-de11-4329-8e03-ec7d9104fc15.png" alt="image" width={200} height={200}/>
<h2 id="toggle">Toggle any position child of parent click</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/210087118-20782374-6605-4457-85db-3e96c020e828.png" alt="image" width={200} height={200}/>
<strong>---------------------------------------------------------------------------------------------------------------------------------------------</strong>
<h2 id="typeTGo">Type T in Go</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/203666154-b492dd4d-fd3d-4a3c-9516-0a4843468b92.png" alt="image" width={200} height={200}/>
<strong>---------------------------------------------------------------------------------------------------------------------------------------------</strong>
<h2 id="quill-next">Import react quill in next js ssr=false</h2><a href="#up">⬆️</a> 
<img src="https://user-images.githubusercontent.com/97892253/209491169-2f2d063a-a887-4559-ac9d-e7360590d770.png" alt="image" width={200} height={200}/>
<h2 id="breakline">Git stash before pull save your code</h2><a href="#up">⬆️</a> 
<div id="stash">
Question:
How i save file not commit before pull

Answer:
You can save your changes without committing them by using the command git stash. This command will save your changes to a new stash, without modifying the git repository's history.
You can then use git pull to update the repository and retrieve any changes made by others. Once you've done that, you can apply your saved changes using the command git stash apply or git stash pop depending on what you want.
Please be aware that if you are working on a branch and there are conflicts after pull, you have to resolve those first before applying stash or doing any other operation

Question:
git stash apply does change your previous change i have saved

Answer:
git stash apply is used to reapply the changes that were previously stashed. When you use this command, the changes from the stash are applied to your working directory. If the changes that you stashed were made to the same lines of code that have been modified in the meantime by other people or you, it can cause conflicts that need to be resolved.

The git stash apply command will not change the stash itself, it will only change the state of your working directory. If you want to keep the stash intact you can use git stash apply command and if you already have the changes and you don't need the stash anymore you can use git stash drop to delete the stash.
</div>
