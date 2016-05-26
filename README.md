
void swap(int *x, int *y);

void main() {
	int i, j;
	i = 10;
	j = 20;
	cout << "Ishodnii: ";
	cout << i << ' ' << j << endl;
	swap(&j, &i);
	cout << "Pomenyal: ";
	cout << i << ' ' << j << endl;

	system("pause");
}

void swap(int *x, int *y) 
{
	int temp;
	temp = *x;
	*x = *y;
	*y = temp;
}
