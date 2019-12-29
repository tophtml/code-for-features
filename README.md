function Staff(name,sales) {
	this.nameSaler = name;
	this.salesSaler = sales;
	this.sum = function(thing) {
		this.salesSaler =+ 1;
	}
}
let salers = ['marry', 'john'];
salers[1] = new Staff('John', 0);
salers[0] = new Staff('Marry', 0);
salers[1].sum('shit');

console.log(salers[0].nameSaler + ' ' + 'sold ' + salers[0].salesSaler + ' things');
console.log(salers[1].nameSaler + ' ' + 'sold ' + salers[1].salesSaler + ' things');
