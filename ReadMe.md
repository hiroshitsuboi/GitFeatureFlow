# Git Feature Flow Template

## Branchs
Master：  
Feature-Branch：masterから作成・開発実装  
Test-ENV：テスト環境と同期（テスト）  
Stg-ENV：ステージング環境と同期されてるBranch  

・環境ごとに、その環境と同期のとれたブランチが存在する(TEST-ENV・Stg-ENVなど)  
・Feature-Branchを環境ごとのブランチにマージする  
・コンフリクト発生時も修正は必ずFeature Branch内で行う（master以外の他のブランチにマージしない）  
・レビューはmasterだけで行う  
・Master + Feature-Branch（FB/xxx） + 各環境ブランチ　で行う  
・  

## コンフリクト
コンフリクトは他のブランチをマージせず、コンフリクトが起きてる2つのブランチを確認しコンフリクトが起きてる「行」だけを正しい形に修正  
コンフリクト時は、それぞれのブランチに最新版のMasterをマージすると解消する場合がある  
他のブランチをマージしないのは、それぞれのブランチの独立性を守るため  



