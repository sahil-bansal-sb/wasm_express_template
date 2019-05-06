# wasm_express_template
Integrated Template of, [express generator](https://expressjs.com/en/starter/generator.html) and [wasm-pack-template](https://github.com/rustwasm/wasm-pack-template)

**:warning: Under Construction**

#### **Note:**  Just remember, its just for practice purposes, if same kind of stuff is required by you, i have also mentioned the steps to create same structure with your own specifications.

## ToDo
-  Add Steps to replicate the structure.
- [ ~ ] Add Steps to use it  

<br>

 - **For Practice purpose**: Steps:
 
         1. Clone the Repo
         2. Change `mainapp/src/` according to requirement.
         3. In `mainapp` run command `wasm-pack build`, it'll create `mainapp/pkg` directory in it.
         4. Create a npm link to pkg by `npm link` command in `mainapp/pkg` directory.
         5. Change `myapp` according to requirement.
         6. Include the link in `myapp` by command `npm link mainapp`.
         7.
