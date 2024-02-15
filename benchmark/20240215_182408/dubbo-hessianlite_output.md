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
# Warmup Iteration   1: 2.106 ops/ms
Iteration   1: 5.150 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.150 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.020 ops/ms
Iteration   1: 9.865 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  9.865 ops/ms


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
# Warmup Iteration   1: 3.593 ops/ms
Iteration   1: 7.597 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.597 ops/ms


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
# Warmup Iteration   1: 1.737 ops/ms
Iteration   1: 2.963 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  2.963 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.451 ±(99.9%) 0.076 ms/op
Iteration   1: 3.620 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.620 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.862 ±(99.9%) 0.050 ms/op
Iteration   1: 1.977 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.977 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.750 ±(99.9%) 0.066 ms/op
Iteration   1: 3.163 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.163 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.533 ±(99.9%) 0.341 ms/op
Iteration   1: 8.177 ±(99.9%) 0.065 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.177 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.080 ±(99.9%) 0.122 ms/op
Iteration   1: 3.001 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   2.773 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   4.350 ms/op
                 createUser·p0.99:   6.295 ms/op
                 createUser·p0.999:  25.224 ms/op
                 createUser·p0.9999: 27.701 ms/op
                 createUser·p1.00:   27.722 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10643
  mean =      3.001 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2178 
    [ 2.500,  5.000) = 8199 
    [ 5.000,  7.500) = 222 
    [ 7.500, 10.000) = 12 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.102 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      3.699 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.295 ms/op
     p(99.9000) =     25.224 ms/op
     p(99.9900) =     27.701 ms/op
     p(99.9990) =     27.722 ms/op
     p(99.9999) =     27.722 ms/op
    p(100.0000) =     27.722 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.284 ±(99.9%) 0.086 ms/op
Iteration   1: 1.797 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.705 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.675 ms/op
                 existUser·p0.99:   3.191 ms/op
                 existUser·p0.999:  3.977 ms/op
                 existUser·p0.9999: 6.071 ms/op
                 existUser·p1.00:   6.455 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17822
  mean =      1.797 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 70 
    [1.000, 1.500) = 4902 
    [1.500, 2.000) = 8139 
    [2.000, 2.500) = 3403 
    [2.500, 3.000) = 954 
    [3.000, 3.500) = 291 
    [3.500, 4.000) = 47 
    [4.000, 4.500) = 4 
    [4.500, 5.000) = 6 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 4 
    [6.000, 6.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.705 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.675 ms/op
     p(99.0000) =      3.191 ms/op
     p(99.9000) =      3.977 ms/op
     p(99.9900) =      6.071 ms/op
     p(99.9990) =      6.455 ms/op
     p(99.9999) =      6.455 ms/op
    p(100.0000) =      6.455 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.765 ±(99.9%) 0.146 ms/op
Iteration   1: 3.433 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.085 ms/op
                 getUser·p0.50:   3.371 ms/op
                 getUser·p0.90:   4.211 ms/op
                 getUser·p0.95:   4.809 ms/op
                 getUser·p0.99:   6.504 ms/op
                 getUser·p0.999:  11.452 ms/op
                 getUser·p0.9999: 11.518 ms/op
                 getUser·p1.00:   11.518 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9359
  mean =      3.433 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 718 
    [ 2.500,  3.750) = 6337 
    [ 3.750,  5.000) = 1903 
    [ 5.000,  6.250) = 292 
    [ 6.250,  7.500) = 65 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 24 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.371 ms/op
     p(90.0000) =      4.211 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      6.504 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     11.518 ms/op
     p(99.9990) =     11.518 ms/op
     p(99.9999) =     11.518 ms/op
    p(100.0000) =     11.518 ms/op


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

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 12.027 ±(99.9%) 0.376 ms/op
Iteration   1: 8.329 ±(99.9%) 0.138 ms/op
                 listUser·p0.00:   1.905 ms/op
                 listUser·p0.50:   7.897 ms/op
                 listUser·p0.90:   10.600 ms/op
                 listUser·p0.95:   11.895 ms/op
                 listUser·p0.99:   22.350 ms/op
                 listUser·p0.999:  27.139 ms/op
                 listUser·p0.9999: 28.344 ms/op
                 listUser·p1.00:   28.344 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3830
  mean =      8.329 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 79 
    [ 5.000,  7.500) = 1434 
    [ 7.500, 10.000) = 1784 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 67 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.905 ms/op
     p(50.0000) =      7.897 ms/op
     p(90.0000) =     10.600 ms/op
     p(95.0000) =     11.895 ms/op
     p(99.0000) =     22.350 ms/op
     p(99.9000) =     27.139 ms/op
     p(99.9900) =     28.344 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.344 ms/op
    p(100.0000) =     28.344 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.150          ops/ms
Client.existUser                       thrpt          9.865          ops/ms
Client.getUser                         thrpt          7.597          ops/ms
Client.listUser                        thrpt          2.963          ops/ms
Client.createUser                       avgt          3.620           ms/op
Client.existUser                        avgt          1.977           ms/op
Client.getUser                          avgt          3.163           ms/op
Client.listUser                         avgt          8.177           ms/op
Client.createUser                     sample  10643   3.001 ± 0.043   ms/op
Client.createUser:createUser·p0.00    sample          1.102           ms/op
Client.createUser:createUser·p0.50    sample          2.773           ms/op
Client.createUser:createUser·p0.90    sample          3.699           ms/op
Client.createUser:createUser·p0.95    sample          4.350           ms/op
Client.createUser:createUser·p0.99    sample          6.295           ms/op
Client.createUser:createUser·p0.999   sample         25.224           ms/op
Client.createUser:createUser·p0.9999  sample         27.701           ms/op
Client.createUser:createUser·p1.00    sample         27.722           ms/op
Client.existUser                      sample  17822   1.797 ± 0.011   ms/op
Client.existUser:existUser·p0.00      sample          0.705           ms/op
Client.existUser:existUser·p0.50      sample          1.702           ms/op
Client.existUser:existUser·p0.90      sample          2.396           ms/op
Client.existUser:existUser·p0.95      sample          2.675           ms/op
Client.existUser:existUser·p0.99      sample          3.191           ms/op
Client.existUser:existUser·p0.999     sample          3.977           ms/op
Client.existUser:existUser·p0.9999    sample          6.071           ms/op
Client.existUser:existUser·p1.00      sample          6.455           ms/op
Client.getUser                        sample   9359   3.433 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          1.085           ms/op
Client.getUser:getUser·p0.50          sample          3.371           ms/op
Client.getUser:getUser·p0.90          sample          4.211           ms/op
Client.getUser:getUser·p0.95          sample          4.809           ms/op
Client.getUser:getUser·p0.99          sample          6.504           ms/op
Client.getUser:getUser·p0.999         sample         11.452           ms/op
Client.getUser:getUser·p0.9999        sample         11.518           ms/op
Client.getUser:getUser·p1.00          sample         11.518           ms/op
Client.listUser                       sample   3830   8.329 ± 0.138   ms/op
Client.listUser:listUser·p0.00        sample          1.905           ms/op
Client.listUser:listUser·p0.50        sample          7.897           ms/op
Client.listUser:listUser·p0.90        sample         10.600           ms/op
Client.listUser:listUser·p0.95        sample         11.895           ms/op
Client.listUser:listUser·p0.99        sample         22.350           ms/op
Client.listUser:listUser·p0.999       sample         27.139           ms/op
Client.listUser:listUser·p0.9999      sample         28.344           ms/op
Client.listUser:listUser·p1.00        sample         28.344           ms/op
