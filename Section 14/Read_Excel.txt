package excel_files;

import java.io.File;
import java.io.FileInputStream;
import java.io.IOException;

import org.apache.poi.xssf.usermodel.XSSFSheet;
import org.apache.poi.xssf.usermodel.XSSFWorkbook;

public class Read_Excel {

	public static void main(String[] args) {
		
		File file = new File("/Users/mayurdeshmukh/Documents/ExcelFiles/File1.xlsx");
		
		XSSFWorkbook wkbook;
		XSSFSheet sheet;
		
		try {
			FileInputStream excel = new FileInputStream(file);
			wkbook = new XSSFWorkbook(excel);
			sheet = wkbook.getSheet("Sheet1");
			int start = sheet.getFirstRowNum();
			int end = sheet.getLastRowNum();
			for(int i = start; i <= end; i++) {
				System.out.print(sheet.getRow(i).getCell(0).getStringCellValue() + "\t");
				System.out.print(sheet.getRow(i).getCell(1).getNumericCellValue() + "\t");
				System.out.print(sheet.getRow(i).getCell(2).getBooleanCellValue() + "\t");
				System.out.println(sheet.getRow(i).getCell(3).getStringCellValue());
			}
			
		} catch(IOException e) {
			System.out.println(e.getMessage());
		}
	}
}
