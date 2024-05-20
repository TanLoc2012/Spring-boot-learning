package com.example.springsecurity.rest.impl;

import org.springframework.http.HttpStatus;
import org.springframework.http.HttpStatusCode;
import org.springframework.http.ResponseEntity;
import org.springframework.web.bind.annotation.GetMapping;
import org.springframework.web.bind.annotation.RequestMapping;
import org.springframework.web.bind.annotation.RestController;

import com.example.springsecurity.rest.IUserRest;

@RestController
@RequestMapping("/api/user")
public class UserRestImpl implements IUserRest {

	@GetMapping(value = "/name")
	public ResponseEntity getUserName() {
		return new ResponseEntity<>("loc", HttpStatus.OK);
	}
}
