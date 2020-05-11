public class WhatHappened {

    boolean exists = true;
    
    public void main(String[] args) {
        Person me = new Person();
        Person myFriend = new Person();
        
        myFriend.askedMeToCreateGitHubAccount();
        me.answeredYes(); 

        if (this.exists) {
            IKeptMyPromise();
        } else {
            IHaventKeptMyPromise();
        }
    }
    
    public void IKeptMyPromise() {
        System.out.println("The account exist. You kept your promise!");
    }
    
    public void IHaventKeptMyPromise() {
        System.out.println("The account doesn't exist. You haven't kept your promise, bastard!");
    }
    
    public class Person {
        public void askedMeToCreateGitHubAccount() {
            System.out.println("Hey!! Can you please create your GitHub acount? :)");
        }

        public void answeredYes() {
            System.out.println("Yes I'll do!");
        }
    }
}
