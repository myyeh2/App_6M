<!--  與ConsoleApp6J相同    -->  
# 精銳矩陣計算求解器(Sharp Matrix Solver, SMS)驗證  

## 測試實例採用 : Jagmohan L. Humar, "Dynamics of Structures Third Editon"  

### ConsoleApp6J採用課本所提供的初始值(Initial Value Problems)  

### 但本例ConsoleApp6M則採用邊界值(Boundary Value Problems)  

由ConsoleApp6J的輸出結果，可得到@ t = 4.5和t = 16.5的初始值如下所示。  
$\quad$
$
@t = 4.5 \quad y_0 =
    \left[
    \begin{matrix}
    -0.68877 \\
    -1.37729  
    \end{matrix}
    \right]
\quad \quad \quad
@t = 16.5 \quad y_0 =
    \left[
    \begin{matrix}
    0.11710 \\
    0.23071  
    \end{matrix}
    \right]
$

### ConsoleApp6J 和 ConsoleApp6M 得到相同的系統與狀態參數，即特徵值 D、特徵向量 Q、和係數向量 d (以上均爲複數陣列)

### 由系統與狀態參數可得系統狀態響應值(變位、速度、和加速度)  

### 故兩個應用程式的響應值完全相 $\Longrightarrow OK$  
