<script>
	import Navigation from './components/Navigation/Navigation';
	import FormInput from './components/FormInput/FormInput';
	import Button from './components/Button/Button';
	import Footer from './components/Footer/Footer';
	import './App.scss';
</script>

<style src="./App.scss"></style>

<div class="main__container">

	<Navigation />

	<form class="form__container">
		<div class="title__container">
		<h1 class="title">Register today <span class="title__ampersand">&</span> </h1>     
		<h1 class="title__secondary">we'll notify you of our launch!</h1>  
		</div> 

		<FormInput 
			inputType={ 'email' } 
			name={ 'email' } 
			classProp={ 'sign__up' } 
			placeholderMsg={ 'Enter your email address....' }
		/>

		<Button 
			btnType={ 'submit' } 
			classType={ 'button' }
			buttonMsg={ 'Submit Email' }
		/>

	</form>

</div>

	<h1 class="large__title">ACME Co.</h1>

<Footer />

