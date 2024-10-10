using System;
using System.Collections.Generic;
class Car
{
    public string Name { get; set; }
    public int ProductionYear { get; set; }
    public int MaxSpeed { get; set; }
    public Car(string name, int productionYear, int maxSpeed)
    {
        Name = name;
        ProductionYear = productionYear;
        MaxSpeed = maxSpeed;
    }
    public override string ToString()
    {
        return $"{Name} ({ProductionYear}), Max Speed: {MaxSpeed} km/h";
    }
}
class CarComparer : IComparer<Car>
{
    public enum SortCriteria
    {
        Name,
        ProductionYear,
        MaxSpeed
    }
    private SortCriteria _sortCriteria;
    public CarComparer(SortCriteria sortCriteria)
    {
        _sortCriteria = sortCriteria;
    }
    public int Compare(Car x, Car y)
    {
        switch (_sortCriteria)
        {
            case SortCriteria.Name:
                return string.Compare(x.Name, y.Name);
            case SortCriteria.ProductionYear:
                return x.ProductionYear.CompareTo(y.ProductionYear);
            case SortCriteria.MaxSpeed:
                return x.MaxSpeed.CompareTo(y.MaxSpeed);
            default:
                throw new ArgumentException("Неизвестный критерий сортировки.");
        }
    }
}
class Program
{
    static void Main(string[] args)
    {
        Car[] cars = new Car[]
        {
            new Car("Toyota", 2015, 220),
            new Car("Honda", 2018, 210),
            new Car("Ford", 2012, 200),
            new Car("BMW", 2020, 250),
            new Car("Audi", 2017, 230)
        };
        Array.Sort(cars, new CarComparer(CarComparer.SortCriteria.Name));
        Console.WriteLine("Сортировка по названию:");
        PrintCars(cars);
        Array.Sort(cars, new CarComparer(CarComparer.SortCriteria.ProductionYear));
        Console.WriteLine("\nСортировка по году выпуска:");
        PrintCars(cars);
        Array.Sort(cars, new CarComparer(CarComparer.SortCriteria.MaxSpeed));
        Console.WriteLine("\nСортировка по максимальной скорости:");
        PrintCars(cars);
    }
    static void PrintCars(Car[] cars)
    {
        foreach (var car in cars)
        {
            Console.WriteLine(car);
        }
    }
}
