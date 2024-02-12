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
# Warmup Iteration   1: 2.321 ops/ms
Iteration   1: 5.602 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.602 ops/ms


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
# Warmup Iteration   1: 5.829 ops/ms
Iteration   1: 13.537 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.537 ops/ms


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
# Warmup Iteration   1: 3.680 ops/ms
Iteration   1: 7.168 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.168 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.005 ops/ms
Iteration   1: 3.429 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.429 ops/ms


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
# Warmup Iteration   1: 5.975 ±(99.9%) 0.083 ms/op
Iteration   1: 3.117 ±(99.9%) 0.043 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.117 ms/op


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
# Warmup Iteration   1: 3.556 ±(99.9%) 0.038 ms/op
Iteration   1: 1.910 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.910 ms/op


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
# Warmup Iteration   1: 5.017 ±(99.9%) 0.081 ms/op
Iteration   1: 3.126 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.126 ms/op


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
# Warmup Iteration   1: 12.915 ±(99.9%) 0.243 ms/op
Iteration   1: 8.764 ±(99.9%) 0.103 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.764 ms/op


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
# Warmup Iteration   1: 5.169 ±(99.9%) 0.103 ms/op
Iteration   1: 3.143 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   4.108 ms/op
                 createUser·p0.95:   4.874 ms/op
                 createUser·p0.99:   6.537 ms/op
                 createUser·p0.999:  8.644 ms/op
                 createUser·p0.9999: 9.144 ms/op
                 createUser·p1.00:   9.159 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10398
  mean =      3.143 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 18 
    [ 1.500,  2.000) = 263 
    [ 2.000,  2.500) = 2039 
    [ 2.500,  3.000) = 2608 
    [ 3.000,  3.500) = 3079 
    [ 3.500,  4.000) = 1261 
    [ 4.000,  4.500) = 352 
    [ 4.500,  5.000) = 344 
    [ 5.000,  5.500) = 205 
    [ 5.500,  6.000) = 80 
    [ 6.000,  6.500) = 42 
    [ 6.500,  7.000) = 59 
    [ 7.000,  7.500) = 16 
    [ 7.500,  8.000) = 10 
    [ 8.000,  8.500) = 8 
    [ 8.500,  9.000) = 13 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.321 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      4.108 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      6.537 ms/op
     p(99.9000) =      8.644 ms/op
     p(99.9900) =      9.144 ms/op
     p(99.9990) =      9.159 ms/op
     p(99.9999) =      9.159 ms/op
    p(100.0000) =      9.159 ms/op


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
# Warmup Iteration   1: 3.610 ±(99.9%) 0.106 ms/op
Iteration   1: 1.849 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.551 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.232 ms/op
                 existUser·p0.95:   2.454 ms/op
                 existUser·p0.99:   3.346 ms/op
                 existUser·p0.999:  28.246 ms/op
                 existUser·p0.9999: 28.511 ms/op
                 existUser·p1.00:   28.606 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17296
  mean =      1.849 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16545 
    [ 2.500,  5.000) = 694 
    [ 5.000,  7.500) = 23 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.551 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.232 ms/op
     p(95.0000) =      2.454 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     28.246 ms/op
     p(99.9900) =     28.511 ms/op
     p(99.9990) =     28.606 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


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
# Warmup Iteration   1: 4.872 ±(99.9%) 0.133 ms/op
Iteration   1: 2.981 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   2.773 ms/op
                 getUser·p0.90:   4.100 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  10.864 ms/op
                 getUser·p0.9999: 12.987 ms/op
                 getUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10908
  mean =      2.981 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3791 
    [ 2.500,  3.750) = 5094 
    [ 3.750,  5.000) = 1709 
    [ 5.000,  6.250) = 163 
    [ 6.250,  7.500) = 90 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 19 
    [10.000, 11.250) = 33 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      2.773 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.555 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     10.864 ms/op
     p(99.9900) =     12.987 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 12.848 ±(99.9%) 0.405 ms/op
Iteration   1: 7.542 ±(99.9%) 0.096 ms/op
                 listUser·p0.00:   2.937 ms/op
                 listUser·p0.50:   7.307 ms/op
                 listUser·p0.90:   9.634 ms/op
                 listUser·p0.95:   10.699 ms/op
                 listUser·p0.99:   14.342 ms/op
                 listUser·p0.999:  20.344 ms/op
                 listUser·p0.9999: 21.889 ms/op
                 listUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4262
  mean =      7.542 ±(99.9%) 0.096 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 168 
    [ 5.000,  7.500) = 2199 
    [ 7.500, 10.000) = 1557 
    [10.000, 12.500) = 260 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.937 ms/op
     p(50.0000) =      7.307 ms/op
     p(90.0000) =      9.634 ms/op
     p(95.0000) =     10.699 ms/op
     p(99.0000) =     14.342 ms/op
     p(99.9000) =     20.344 ms/op
     p(99.9900) =     21.889 ms/op
     p(99.9990) =     21.889 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.602          ops/ms
Client.existUser                       thrpt         13.537          ops/ms
Client.getUser                         thrpt          7.168          ops/ms
Client.listUser                        thrpt          3.429          ops/ms
Client.createUser                       avgt          3.117           ms/op
Client.existUser                        avgt          1.910           ms/op
Client.getUser                          avgt          3.126           ms/op
Client.listUser                         avgt          8.764           ms/op
Client.createUser                     sample  10398   3.143 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          1.321           ms/op
Client.createUser:createUser·p0.50    sample          3.047           ms/op
Client.createUser:createUser·p0.90    sample          4.108           ms/op
Client.createUser:createUser·p0.95    sample          4.874           ms/op
Client.createUser:createUser·p0.99    sample          6.537           ms/op
Client.createUser:createUser·p0.999   sample          8.644           ms/op
Client.createUser:createUser·p0.9999  sample          9.144           ms/op
Client.createUser:createUser·p1.00    sample          9.159           ms/op
Client.existUser                      sample  17296   1.849 ± 0.030   ms/op
Client.existUser:existUser·p0.00      sample          0.551           ms/op
Client.existUser:existUser·p0.50      sample          1.745           ms/op
Client.existUser:existUser·p0.90      sample          2.232           ms/op
Client.existUser:existUser·p0.95      sample          2.454           ms/op
Client.existUser:existUser·p0.99      sample          3.346           ms/op
Client.existUser:existUser·p0.999     sample         28.246           ms/op
Client.existUser:existUser·p0.9999    sample         28.511           ms/op
Client.existUser:existUser·p1.00      sample         28.606           ms/op
Client.getUser                        sample  10908   2.981 ± 0.032   ms/op
Client.getUser:getUser·p0.00          sample          1.313           ms/op
Client.getUser:getUser·p0.50          sample          2.773           ms/op
Client.getUser:getUser·p0.90          sample          4.100           ms/op
Client.getUser:getUser·p0.95          sample          4.555           ms/op
Client.getUser:getUser·p0.99          sample          6.742           ms/op
Client.getUser:getUser·p0.999         sample         10.864           ms/op
Client.getUser:getUser·p0.9999        sample         12.987           ms/op
Client.getUser:getUser·p1.00          sample         13.009           ms/op
Client.listUser                       sample   4262   7.542 ± 0.096   ms/op
Client.listUser:listUser·p0.00        sample          2.937           ms/op
Client.listUser:listUser·p0.50        sample          7.307           ms/op
Client.listUser:listUser·p0.90        sample          9.634           ms/op
Client.listUser:listUser·p0.95        sample         10.699           ms/op
Client.listUser:listUser·p0.99        sample         14.342           ms/op
Client.listUser:listUser·p0.999       sample         20.344           ms/op
Client.listUser:listUser·p0.9999      sample         21.889           ms/op
Client.listUser:listUser·p1.00        sample         21.889           ms/op
