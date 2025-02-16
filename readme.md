{"nbformat":4,"nbformat_minor":0,"metadata":{"colab":{"provenance":[],"authorship_tag":"ABX9TyM5s4zaEqthUf9GGwffAsLk"},"kernelspec":{"name":"python3","display_name":"Python 3"},"language_info":{"name":"python"}},"cells":[{"cell_type":"code","source":["from google.colab import drive\n","drive.mount('/content/drive')"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"id":"Hnm9saqdeC5Y","executionInfo":{"status":"ok","timestamp":1739721628765,"user_tz":-480,"elapsed":6064,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"24c9bc1d-0b8c-45ee-a1d7-f92a33c8d648"},"execution_count":7,"outputs":[{"output_type":"stream","name":"stdout","text":["Drive already mounted at /content/drive; to attempt to forcibly remount, call drive.mount(\"/content/drive\", force_remount=True).\n"]}]},{"cell_type":"code","source":["cd /content/drive/MyDrive/Github/"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"id":"P66hl-U6egJy","executionInfo":{"status":"ok","timestamp":1739721872528,"user_tz":-480,"elapsed":454,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"e77d2d4e-ac95-45bb-e44b-3fd44f7f504d"},"execution_count":11,"outputs":[{"output_type":"stream","name":"stdout","text":["/content/drive/MyDrive/Github\n"]}]},{"cell_type":"code","source":["!git init titanic"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"collapsed":true,"id":"C-7EYb7uhizY","executionInfo":{"status":"ok","timestamp":1739722236348,"user_tz":-480,"elapsed":667,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"b071081f-f44c-4ad0-a843-4777b0671063"},"execution_count":13,"outputs":[{"output_type":"stream","name":"stdout","text":["\u001b[33mhint: Using 'master' as the name for the initial branch. This default branch name\u001b[m\n","\u001b[33mhint: is subject to change. To configure the initial branch name to use in all\u001b[m\n","\u001b[33mhint: of your new repositories, which will suppress this warning, call:\u001b[m\n","\u001b[33mhint: \u001b[m\n","\u001b[33mhint: \tgit config --global init.defaultBranch <name>\u001b[m\n","\u001b[33mhint: \u001b[m\n","\u001b[33mhint: Names commonly chosen instead of 'master' are 'main', 'trunk' and\u001b[m\n","\u001b[33mhint: 'development'. The just-created branch can be renamed via this command:\u001b[m\n","\u001b[33mhint: \u001b[m\n","\u001b[33mhint: \tgit branch -m <name>\u001b[m\n","Initialized empty Git repository in /content/drive/MyDrive/Github/titanic/.git/\n"]}]},{"cell_type":"code","source":["%cd titanic/"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"id":"6V0geZfihuC3","executionInfo":{"status":"ok","timestamp":1739722268361,"user_tz":-480,"elapsed":594,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"65308962-9711-4097-d91c-cb7642b1fc55"},"execution_count":14,"outputs":[{"output_type":"stream","name":"stdout","text":["/content/drive/MyDrive/Github/titanic\n"]}]},{"cell_type":"code","source":["%ls -a"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"id":"qHkSNBSvh0ON","executionInfo":{"status":"ok","timestamp":1739722283818,"user_tz":-480,"elapsed":530,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"498fedd6-54c8-4288-9565-1fe587e0a9f7"},"execution_count":15,"outputs":[{"output_type":"stream","name":"stdout","text":["\u001b[0m\u001b[01;34m.git\u001b[0m/\n"]}]},{"cell_type":"code","source":["!git status"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"id":"s_IDqZzSh5WT","executionInfo":{"status":"ok","timestamp":1739722308564,"user_tz":-480,"elapsed":600,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"966feae7-c8a0-427c-f427-73daf84500b5"},"execution_count":16,"outputs":[{"output_type":"stream","name":"stdout","text":["On branch master\n","\n","No commits yet\n","\n","nothing to commit (create/copy files and use \"git add\" to track)\n"]}]},{"cell_type":"code","source":["!git add ."],"metadata":{"id":"R-1Bhy6oh_Rw","executionInfo":{"status":"ok","timestamp":1739723466843,"user_tz":-480,"elapsed":617,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}}},"execution_count":27,"outputs":[]},{"cell_type":"markdown","source":["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\n","\n","```\n","# This is formatted as code\n","```\n","\n"],"metadata":{"id":"WvCYkIbVkA7s"}},{"cell_type":"code","source":["!git status"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"id":"kYiFiw7jiJvz","executionInfo":{"status":"ok","timestamp":1739722373105,"user_tz":-480,"elapsed":547,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"6e94b18a-56e1-42e5-8d8a-a0031b22727f"},"execution_count":19,"outputs":[{"output_type":"stream","name":"stdout","text":["On branch master\n","\n","No commits yet\n","\n","nothing to commit (create/copy files and use \"git add\" to track)\n"]}]},{"cell_type":"code","source":["username = 'DT-1999'\n","git_token = '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'\n","repository = 'titanic'"],"metadata":{"id":"aqWIHiLojbaY","executionInfo":{"status":"ok","timestamp":1739723262863,"user_tz":-480,"elapsed":620,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}}},"execution_count":24,"outputs":[]},{"cell_type":"code","source":["!git remote add origin https://{git_token}@github.com/{username}/{repository}.git\n","!git remote -v"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"id":"OZjqBb-cllch","executionInfo":{"status":"ok","timestamp":1739723320882,"user_tz":-480,"elapsed":592,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"05d62d35-5471-4cda-90f1-d61da561f68c"},"execution_count":25,"outputs":[{"output_type":"stream","name":"stdout","text":["origin\thttps://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@github.com/DT-1999/titanic.git (fetch)\n","origin\thttps://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@github.com/DT-1999/titanic.git (push)\n"]}]},{"cell_type":"code","source":["!git push -u origin master"],"metadata":{"colab":{"base_uri":"https://localhost:8080/"},"id":"mDHlEALHl1wi","executionInfo":{"status":"ok","timestamp":1739723351857,"user_tz":-480,"elapsed":683,"user":{"displayName":"Tao Deng","userId":"10119685646103841295"}},"outputId":"620a6722-2794-4e21-a7f0-f6f91bb03656"},"execution_count":26,"outputs":[{"output_type":"stream","name":"stdout","text":["error: src refspec master does not match any\n","\u001b[31merror: failed to push some refs to 'https://github.com/DT-1999/titanic.git'\n","\u001b[m"]}]}]}