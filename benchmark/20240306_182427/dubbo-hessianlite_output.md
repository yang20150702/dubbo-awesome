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
# Warmup Iteration   1: 2.427 ops/ms
Iteration   1: 6.336 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.336 ops/ms


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
# Warmup Iteration   1: 6.537 ops/ms
Iteration   1: 12.000 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.000 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.261 ops/ms
Iteration   1: 9.057 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.057 ops/ms


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
# Warmup Iteration   1: 2.317 ops/ms
Iteration   1: 3.613 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.613 ops/ms


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
# Warmup Iteration   1: 5.189 ±(99.9%) 0.131 ms/op
Iteration   1: 3.051 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.051 ms/op


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
# Warmup Iteration   1: 3.573 ±(99.9%) 0.041 ms/op
Iteration   1: 2.082 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.082 ms/op


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
# Warmup Iteration   1: 4.505 ±(99.9%) 0.063 ms/op
Iteration   1: 3.236 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.236 ms/op


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
# Warmup Iteration   1: 12.931 ±(99.9%) 0.370 ms/op
Iteration   1: 8.617 ±(99.9%) 0.064 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.617 ms/op


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
# Warmup Iteration   1: 5.010 ±(99.9%) 0.109 ms/op
Iteration   1: 3.056 ±(99.9%) 0.061 ms/op
                 createUser·p0.00:   0.935 ms/op
                 createUser·p0.50:   2.839 ms/op
                 createUser·p0.90:   3.576 ms/op
                 createUser·p0.95:   3.997 ms/op
                 createUser·p0.99:   9.508 ms/op
                 createUser·p0.999:  30.034 ms/op
                 createUser·p0.9999: 32.129 ms/op
                 createUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10441
  mean =      3.056 ±(99.9%) 0.061 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3547 
    [ 2.500,  5.000) = 6580 
    [ 5.000,  7.500) = 121 
    [ 7.500, 10.000) = 102 
    [10.000, 12.500) = 30 
    [12.500, 15.000) = 23 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.935 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.576 ms/op
     p(95.0000) =      3.997 ms/op
     p(99.0000) =      9.508 ms/op
     p(99.9000) =     30.034 ms/op
     p(99.9900) =     32.129 ms/op
     p(99.9990) =     32.145 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


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
# Warmup Iteration   1: 3.133 ±(99.9%) 0.075 ms/op
Iteration   1: 1.824 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.575 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.257 ms/op
                 existUser·p0.95:   2.441 ms/op
                 existUser·p0.99:   2.747 ms/op
                 existUser·p0.999:  3.744 ms/op
                 existUser·p0.9999: 5.909 ms/op
                 existUser·p1.00:   5.947 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17727
  mean =      1.824 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 125 
    [1.000, 1.500) = 2561 
    [1.500, 2.000) = 10053 
    [2.000, 2.500) = 4292 
    [2.500, 3.000) = 634 
    [3.000, 3.500) = 25 
    [3.500, 4.000) = 31 
    [4.000, 4.500) = 1 
    [4.500, 5.000) = 0 
    [5.000, 5.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.257 ms/op
     p(95.0000) =      2.441 ms/op
     p(99.0000) =      2.747 ms/op
     p(99.9000) =      3.744 ms/op
     p(99.9900) =      5.909 ms/op
     p(99.9990) =      5.947 ms/op
     p(99.9999) =      5.947 ms/op
    p(100.0000) =      5.947 ms/op


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
# Warmup Iteration   1: 4.457 ±(99.9%) 0.104 ms/op
Iteration   1: 3.181 ±(99.9%) 0.054 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.497 ms/op
                 getUser·p0.99:   10.144 ms/op
                 getUser·p0.999:  27.850 ms/op
                 getUser·p0.9999: 29.062 ms/op
                 getUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10091
  mean =      3.181 ±(99.9%) 0.054 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1891 
    [ 2.500,  5.000) = 7908 
    [ 5.000,  7.500) = 191 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.497 ms/op
     p(99.0000) =     10.144 ms/op
     p(99.9000) =     27.850 ms/op
     p(99.9900) =     29.062 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


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
# Warmup Iteration   1: 11.471 ±(99.9%) 0.375 ms/op
Iteration   1: 8.774 ±(99.9%) 0.155 ms/op
                 listUser·p0.00:   1.161 ms/op
                 listUser·p0.50:   8.184 ms/op
                 listUser·p0.90:   12.357 ms/op
                 listUser·p0.95:   14.051 ms/op
                 listUser·p0.99:   17.565 ms/op
                 listUser·p0.999:  28.970 ms/op
                 listUser·p0.9999: 34.931 ms/op
                 listUser·p1.00:   34.931 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3647
  mean =      8.774 ±(99.9%) 0.155 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 81 
    [ 5.000,  7.500) = 1312 
    [ 7.500, 10.000) = 1291 
    [10.000, 12.500) = 622 
    [12.500, 15.000) = 196 
    [15.000, 17.500) = 106 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.161 ms/op
     p(50.0000) =      8.184 ms/op
     p(90.0000) =     12.357 ms/op
     p(95.0000) =     14.051 ms/op
     p(99.0000) =     17.565 ms/op
     p(99.9000) =     28.970 ms/op
     p(99.9900) =     34.931 ms/op
     p(99.9990) =     34.931 ms/op
     p(99.9999) =     34.931 ms/op
    p(100.0000) =     34.931 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.336          ops/ms
Client.existUser                       thrpt         12.000          ops/ms
Client.getUser                         thrpt          9.057          ops/ms
Client.listUser                        thrpt          3.613          ops/ms
Client.createUser                       avgt          3.051           ms/op
Client.existUser                        avgt          2.082           ms/op
Client.getUser                          avgt          3.236           ms/op
Client.listUser                         avgt          8.617           ms/op
Client.createUser                     sample  10441   3.056 ± 0.061   ms/op
Client.createUser:createUser·p0.00    sample          0.935           ms/op
Client.createUser:createUser·p0.50    sample          2.839           ms/op
Client.createUser:createUser·p0.90    sample          3.576           ms/op
Client.createUser:createUser·p0.95    sample          3.997           ms/op
Client.createUser:createUser·p0.99    sample          9.508           ms/op
Client.createUser:createUser·p0.999   sample         30.034           ms/op
Client.createUser:createUser·p0.9999  sample         32.129           ms/op
Client.createUser:createUser·p1.00    sample         32.145           ms/op
Client.existUser                      sample  17727   1.824 ± 0.009   ms/op
Client.existUser:existUser·p0.00      sample          0.575           ms/op
Client.existUser:existUser·p0.50      sample          1.802           ms/op
Client.existUser:existUser·p0.90      sample          2.257           ms/op
Client.existUser:existUser·p0.95      sample          2.441           ms/op
Client.existUser:existUser·p0.99      sample          2.747           ms/op
Client.existUser:existUser·p0.999     sample          3.744           ms/op
Client.existUser:existUser·p0.9999    sample          5.909           ms/op
Client.existUser:existUser·p1.00      sample          5.947           ms/op
Client.getUser                        sample  10091   3.181 ± 0.054   ms/op
Client.getUser:getUser·p0.00          sample          0.833           ms/op
Client.getUser:getUser·p0.50          sample          2.978           ms/op
Client.getUser:getUser·p0.90          sample          3.883           ms/op
Client.getUser:getUser·p0.95          sample          4.497           ms/op
Client.getUser:getUser·p0.99          sample         10.144           ms/op
Client.getUser:getUser·p0.999         sample         27.850           ms/op
Client.getUser:getUser·p0.9999        sample         29.062           ms/op
Client.getUser:getUser·p1.00          sample         29.065           ms/op
Client.listUser                       sample   3647   8.774 ± 0.155   ms/op
Client.listUser:listUser·p0.00        sample          1.161           ms/op
Client.listUser:listUser·p0.50        sample          8.184           ms/op
Client.listUser:listUser·p0.90        sample         12.357           ms/op
Client.listUser:listUser·p0.95        sample         14.051           ms/op
Client.listUser:listUser·p0.99        sample         17.565           ms/op
Client.listUser:listUser·p0.999       sample         28.970           ms/op
Client.listUser:listUser·p0.9999      sample         34.931           ms/op
Client.listUser:listUser·p1.00        sample         34.931           ms/op
