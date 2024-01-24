# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.169 ops/ms
Iteration   1: 5.486 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.486 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.364 ops/ms
Iteration   1: 13.875 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.875 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.277 ops/ms
Iteration   1: 8.524 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.524 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.860 ops/ms
Iteration   1: 3.523 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.523 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.808 ±(99.9%) 0.094 ms/op
Iteration   1: 2.978 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.978 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.406 ±(99.9%) 0.036 ms/op
Iteration   1: 2.039 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.039 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.832 ±(99.9%) 0.045 ms/op
Iteration   1: 3.375 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.375 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 13.036 ±(99.9%) 0.359 ms/op
Iteration   1: 8.628 ±(99.9%) 0.110 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.628 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 4.918 ±(99.9%) 0.098 ms/op
Iteration   1: 3.015 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.905 ms/op
                 createUser·p0.50:   2.847 ms/op
                 createUser·p0.90:   3.961 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  12.263 ms/op
                 createUser·p0.9999: 15.594 ms/op
                 createUser·p1.00:   15.745 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10500
  mean =      3.015 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2493 
    [ 2.500,  3.750) = 6396 
    [ 3.750,  5.000) = 1436 
    [ 5.000,  6.250) = 73 
    [ 6.250,  7.500) = 39 
    [ 7.500,  8.750) = 13 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.905 ms/op
     p(50.0000) =      2.847 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.202 ms/op
     p(99.0000) =      5.710 ms/op
     p(99.9000) =     12.263 ms/op
     p(99.9900) =     15.594 ms/op
     p(99.9990) =     15.745 ms/op
     p(99.9999) =     15.745 ms/op
    p(100.0000) =     15.745 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.283 ±(99.9%) 0.081 ms/op
Iteration   1: 1.872 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.570 ms/op
                 existUser·p0.50:   1.806 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.589 ms/op
                 existUser·p0.99:   3.743 ms/op
                 existUser·p0.999:  8.432 ms/op
                 existUser·p0.9999: 8.913 ms/op
                 existUser·p1.00:   8.913 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17122
  mean =      1.872 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 248 
    [1.000, 1.500) = 2998 
    [1.500, 2.000) = 8774 
    [2.000, 2.500) = 3875 
    [2.500, 3.000) = 929 
    [3.000, 3.500) = 96 
    [3.500, 4.000) = 101 
    [4.000, 4.500) = 9 
    [4.500, 5.000) = 0 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 39 
    [8.000, 8.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.570 ms/op
     p(50.0000) =      1.806 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.589 ms/op
     p(99.0000) =      3.743 ms/op
     p(99.9000) =      8.432 ms/op
     p(99.9900) =      8.913 ms/op
     p(99.9990) =      8.913 ms/op
     p(99.9999) =      8.913 ms/op
    p(100.0000) =      8.913 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.590 ±(99.9%) 0.110 ms/op
Iteration   1: 3.168 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   0.603 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.969 ms/op
                 getUser·p0.95:   4.293 ms/op
                 getUser·p0.99:   6.019 ms/op
                 getUser·p0.999:  8.649 ms/op
                 getUser·p0.9999: 10.975 ms/op
                 getUser·p1.00:   10.977 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10120
  mean =      3.168 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 2108 
    [ 2.500,  3.750) = 6303 
    [ 3.750,  5.000) = 1481 
    [ 5.000,  6.250) = 125 
    [ 6.250,  7.500) = 76 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.603 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.969 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      6.019 ms/op
     p(99.9000) =      8.649 ms/op
     p(99.9900) =     10.975 ms/op
     p(99.9990) =     10.977 ms/op
     p(99.9999) =     10.977 ms/op
    p(100.0000) =     10.977 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.184 ±(99.9%) 0.454 ms/op
Iteration   1: 8.617 ±(99.9%) 0.114 ms/op
                 listUser·p0.00:   3.228 ms/op
                 listUser·p0.50:   8.364 ms/op
                 listUser·p0.90:   10.994 ms/op
                 listUser·p0.95:   11.922 ms/op
                 listUser·p0.99:   17.400 ms/op
                 listUser·p0.999:  20.730 ms/op
                 listUser·p0.9999: 21.791 ms/op
                 listUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3726
  mean =      8.617 ±(99.9%) 0.114 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 48 
    [ 5.000,  7.500) = 1071 
    [ 7.500, 10.000) = 1876 
    [10.000, 12.500) = 593 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.228 ms/op
     p(50.0000) =      8.364 ms/op
     p(90.0000) =     10.994 ms/op
     p(95.0000) =     11.922 ms/op
     p(99.0000) =     17.400 ms/op
     p(99.9000) =     20.730 ms/op
     p(99.9900) =     21.791 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.486          ops/ms
Client.existUser                       thrpt         13.875          ops/ms
Client.getUser                         thrpt          8.524          ops/ms
Client.listUser                        thrpt          3.523          ops/ms
Client.createUser                       avgt          2.978           ms/op
Client.existUser                        avgt          2.039           ms/op
Client.getUser                          avgt          3.375           ms/op
Client.listUser                         avgt          8.628           ms/op
Client.createUser                     sample  10500   3.015 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          0.905           ms/op
Client.createUser:createUser·p0.50    sample          2.847           ms/op
Client.createUser:createUser·p0.90    sample          3.961           ms/op
Client.createUser:createUser·p0.95    sample          4.202           ms/op
Client.createUser:createUser·p0.99    sample          5.710           ms/op
Client.createUser:createUser·p0.999   sample         12.263           ms/op
Client.createUser:createUser·p0.9999  sample         15.594           ms/op
Client.createUser:createUser·p1.00    sample         15.745           ms/op
Client.existUser                      sample  17122   1.872 ± 0.016   ms/op
Client.existUser:existUser·p0.00      sample          0.570           ms/op
Client.existUser:existUser·p0.50      sample          1.806           ms/op
Client.existUser:existUser·p0.90      sample          2.396           ms/op
Client.existUser:existUser·p0.95      sample          2.589           ms/op
Client.existUser:existUser·p0.99      sample          3.743           ms/op
Client.existUser:existUser·p0.999     sample          8.432           ms/op
Client.existUser:existUser·p0.9999    sample          8.913           ms/op
Client.existUser:existUser·p1.00      sample          8.913           ms/op
Client.getUser                        sample  10120   3.168 ± 0.026   ms/op
Client.getUser:getUser·p0.00          sample          0.603           ms/op
Client.getUser:getUser·p0.50          sample          3.183           ms/op
Client.getUser:getUser·p0.90          sample          3.969           ms/op
Client.getUser:getUser·p0.95          sample          4.293           ms/op
Client.getUser:getUser·p0.99          sample          6.019           ms/op
Client.getUser:getUser·p0.999         sample          8.649           ms/op
Client.getUser:getUser·p0.9999        sample         10.975           ms/op
Client.getUser:getUser·p1.00          sample         10.977           ms/op
Client.listUser                       sample   3726   8.617 ± 0.114   ms/op
Client.listUser:listUser·p0.00        sample          3.228           ms/op
Client.listUser:listUser·p0.50        sample          8.364           ms/op
Client.listUser:listUser·p0.90        sample         10.994           ms/op
Client.listUser:listUser·p0.95        sample         11.922           ms/op
Client.listUser:listUser·p0.99        sample         17.400           ms/op
Client.listUser:listUser·p0.999       sample         20.730           ms/op
Client.listUser:listUser·p0.9999      sample         21.791           ms/op
Client.listUser:listUser·p1.00        sample         21.791           ms/op
