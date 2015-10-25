# Bible

$(document).ready(function() {
	$('#genesis').click(function () {
		$('#readExodus').hide();
		$('#watchexo').hide();
		$('#readLeviticus').hide();
		$('#readNumbers').hide();
		$('#readDeuteronomy').hide();
		$('#readJoshua').hide();
		$('#watchGen').hide();



		$('#readGenesis').fadeIn();
	});

	$('#exovideo').click(function () {
		$('#readExodus').hide();
		$('#readLeviticus').hide();
		$('#readNumbers').hide();
		$('#readDeuteronomy').hide();
		$('#readJoshua').hide();
		$('#watchGen').hide();


		$('#watchgen').hide();
		$('#watchexo').show();
	});

	$('#exodus').click(function () {
		$('#readLeviticus').hide();
		$('#readNumbers').hide();
		$('#readDeuteronomy').hide();
		$('#readJoshua').hide();

		$('#readGenesis').hide();
		$('#watchGen').hide();
		$('#readExodus').fadeIn();
		$('#watchexo').hide();
	});

	$('#exovideo').click(function () {
		$('#readExodus').hide();
		$('#readLeviticus').hide();
		$('#readNumbers').hide();
		$('#readDeuteronomy').hide();
		$('#readJoshua').hide();
		$('#watchGen').hide();


		$('#watchexo').show();
	});

	$('#leviticus').click(function () {
		$('#readNumbers').hide();
		$('#readDeuteronomy').hide();
		$('#readJoshua').hide();

		$('#readExodus').hide();
		$('#watchexo').hide();
		$('#readGenesis').hide();
		$('#watchGen').hide();
		$('#readLeviticus').fadeIn();
	});

	$('#numbers').click(function () {

		$('#readDeuteronomy').hide();
		$('#readJoshua').hide();

		$('#readExodus').hide();
		$('#watchexo').hide();
		$('#readGenesis').hide();
		$('#watchGen').hide();
		$('#readLeviticus').hide();
		$('#readNumbers').fadeIn();
	});

	$('#deuteronomy').click(function () {

		$('#readJoshua').hide();

		$('#readExodus').hide();
		$('#watchexo').hide();
		$('#readGenesis').hide();
		$('#watchGen').hide();
		$('#readLeviticus').hide();
		$('#readNumbers').hide();
		$('#readDeuteronomy').fadeIn();
	});

	$('#joshua').click(function () {

		
		$('#readExodus').hide();
		$('#watchexo').hide();
		$('#readGenesis').hide();
		$('#watchGen').hide();
		$('#readLeviticus').hide();
		$('#readNumbers').hide();
		$('#readDeuteronomy').hide();

		$('#readJoshua').fadeIn();
	});
});

