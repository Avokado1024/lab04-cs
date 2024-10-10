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
class CarCollection
{
    private List<Car> cars;

    public CarCollection(List<Car> cars)
    {
        this.cars = cars;
    }
    public IEnumerable<Car> GetCarsByProductionYear(int year)
    {
        foreach (var car in cars)
        {
            if (car.ProductionYear == year)
            {
                yield return car;
            }
        }
    }
    public IEnumerable<Car> GetCarsByMaxSpeed(int speed)
    {
        foreach (var car in cars)
        {
            if (car.MaxSpeed == speed)
            {
                yield return car;
            }
        }
    }
}
class Program
{
    static void Main(string[] args)
    {
        List<Car> cars = new List<Car>
        {
            new Car("Toyota", 2015, 220),
            new Car("Honda", 2018, 210),
            new Car("Ford", 2012, 200),
            new Car("BMW", 2020, 250),
            new Car("Audi", 2017, 230)
        };
        CarCollection carCollection = new CarCollection(cars);
        cars.Sort(new CarComparer(CarComparer.SortCriteria.Name));
        Console.WriteLine("Сортировка по названию:");
        PrintCars(cars);
        cars.Sort(new CarComparer(CarComparer.SortCriteria.ProductionYear));
        Console.WriteLine("\nСортировка по году выпуска:");
        PrintCars(cars);
        cars.Sort(new CarComparer(CarComparer.SortCriteria.MaxSpeed));
        Console.WriteLine("\nСортировка по максимальной скорости:");
        PrintCars(cars);
        Console.WriteLine("\nАвтомобили, выпущенные в 2018 году:");
        foreach (var car in carCollection.GetCarsByProductionYear(2018))
        {
            Console.WriteLine(car);
        }
        Console.WriteLine("\nАвтомобили с максимальной скоростью 220 км/ч:");
        foreach (var car in carCollection.GetCarsByMaxSpeed(220))
        {
            Console.WriteLine(car);
        }
    }
    static void PrintCars(List<Car> cars)
    {
        foreach (var car in cars)
        {
            Console.WriteLine(car);
        }
    }
}
