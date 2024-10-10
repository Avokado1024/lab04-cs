using System;
class MyMatrix
{
    private int[,] matrix;
    private int rows;
    private int cols;
    private Random random = new Random();
    public MyMatrix(int rows, int cols, int minValue, int maxValue)
    {
        this.rows = rows;
        this.cols = cols;
        matrix = new int[rows, cols];
        for (int i = 0; i < rows; i++)
        {
            for (int j = 0; j < cols; j++)
            {
                matrix[i, j] = random.Next(minValue, maxValue + 1);
            }
        }
    }
    public int this[int row, int col]
    {
        get { return matrix[row, col]; }
        set { matrix[row, col] = value; }
    }
    public static MyMatrix operator +(MyMatrix a, MyMatrix b)
    {
        if (a.rows != b.rows || a.cols != b.cols)
        {
            throw new ArgumentException("Матрицы должны иметь одинаковые размеры для сложения.");
        }
        MyMatrix result = new MyMatrix(a.rows, a.cols, 0, 0);
        for (int i = 0; i < a.rows; i++)
        {
            for (int j = 0; j < a.cols; j++)
            {
                result[i, j] = a[i, j] + b[i, j];
            }
        }
        return result;
    }
    public static MyMatrix operator -(MyMatrix a, MyMatrix b)
    {
        if (a.rows != b.rows || a.cols != b.cols)
        {
            throw new ArgumentException("Матрицы должны иметь одинаковые размеры для вычитания.");
        }
        MyMatrix result = new MyMatrix(a.rows, a.cols, 0, 0);
        for (int i = 0; i < a.rows; i++)
        {
            for (int j = 0; j < a.cols; j++)
            {
                result[i, j] = a[i, j] - b[i, j];
            }
        }
        return result;
    }
    public static MyMatrix operator *(MyMatrix a, MyMatrix b)
    {
        if (a.cols != b.rows)
        {
            throw new ArgumentException("Количество столбцов первой матрицы должно быть равно количеству строк второй матрицы для умножения.");
        }
        MyMatrix result = new MyMatrix(a.rows, b.cols, 0, 0);
        for (int i = 0; i < a.rows; i++)
        {
            for (int j = 0; j < b.cols; j++)
            {
                int sum = 0;
                for (int k = 0; k < a.cols; k++)
                {
                    sum += a[i, k] * b[k, j];
                }
                result[i, j] = sum;
            }
        }
        return result;
    }
    public static MyMatrix operator *(MyMatrix a, int scalar)
    {
        MyMatrix result = new MyMatrix(a.rows, a.cols, 0, 0);
        for (int i = 0; i < a.rows; i++)
        {
            for (int j = 0; j < a.cols; j++)
            {
                result[i, j] = a[i, j] * scalar;
            }
        }
        return result;
    }
    public static MyMatrix operator /(MyMatrix a, int scalar)
    {
        if (scalar == 0)
        {
            throw new DivideByZeroException("Деление на ноль невозможно.");
        }
        MyMatrix result = new MyMatrix(a.rows, a.cols, 0, 0);
        for (int i = 0; i < a.rows; i++)
        {
            for (int j = 0; j < a.cols; j++)
            {
                result[i, j] = a[i, j] / scalar;
            }
        }
        return result;
    }
    public void PrintMatrix()
    {
        for (int i = 0; i < rows; i++)
        {
            for (int j = 0; j < cols; j++)
            {
                Console.Write(matrix[i, j] + "\t");
            }
            Console.WriteLine();
        }
    }
}
class Program
{
    static void Main(string[] args)
    {
        Console.Write("Введите количество строк матрицы: ");
        int rows = int.Parse(Console.ReadLine());
        Console.Write("Введите количество столбцов матрицы: ");
        int cols = int.Parse(Console.ReadLine());
        Console.Write("Введите минимальное значение для случайных чисел: ");
        int minValue = int.Parse(Console.ReadLine());
        Console.Write("Введите максимальное значение для случайных чисел: ");
        int maxValue = int.Parse(Console.ReadLine());
        MyMatrix matrix1 = new MyMatrix(rows, cols, minValue, maxValue);
        MyMatrix matrix2 = new MyMatrix(rows, cols, minValue, maxValue);
        Console.WriteLine("Матрица 1:");
        matrix1.PrintMatrix();
        Console.WriteLine("Матрица 2:");
        matrix2.PrintMatrix();
        MyMatrix sumMatrix = matrix1 + matrix2;
        Console.WriteLine("Сумма матриц:");
        sumMatrix.PrintMatrix();
        MyMatrix diffMatrix = matrix1 - matrix2;
        Console.WriteLine("Разность матриц:");
        diffMatrix.PrintMatrix();
        MyMatrix productMatrix = matrix1 * matrix2;
        Console.WriteLine("Произведение матриц:");
        productMatrix.PrintMatrix();
        Console.Write("Введите число для умножения матрицы 1: ");
        int scalar = int.Parse(Console.ReadLine());
        MyMatrix scaledMatrix = matrix1 * scalar;
        Console.WriteLine("Матрица 1, умноженная на число:");
        scaledMatrix.PrintMatrix();
        Console.Write("Введите число для деления матрицы 1: ");
        scalar = int.Parse(Console.ReadLine());
        MyMatrix dividedMatrix = matrix1 / scalar;
        Console.WriteLine("Матрица 1, деленная на число:");
        dividedMatrix.PrintMatrix();
    }
}
