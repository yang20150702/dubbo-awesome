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
# Warmup Iteration   1: 2.253 ops/ms
Iteration   1: 6.297 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.297 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:16
# Fork: 1 of 1
# Warmup Iteration   1: 5.502 ops/ms
Iteration   1: 10.821 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.821 ops/ms


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
# Warmup Iteration   1: 3.494 ops/ms
Iteration   1: 8.311 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.311 ops/ms


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
# Warmup Iteration   1: 1.869 ops/ms
Iteration   1: 3.386 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.386 ops/ms


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
# Warmup Iteration   1: 5.744 ±(99.9%) 0.083 ms/op
Iteration   1: 3.062 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.062 ms/op


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
# Warmup Iteration   1: 3.614 ±(99.9%) 0.060 ms/op
Iteration   1: 1.985 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.985 ms/op


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
# Warmup Iteration   1: 4.950 ±(99.9%) 0.061 ms/op
Iteration   1: 3.209 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.209 ms/op


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
# Warmup Iteration   1: 12.698 ±(99.9%) 0.292 ms/op
Iteration   1: 8.181 ±(99.9%) 0.102 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.181 ms/op


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
# Warmup Iteration   1: 5.050 ±(99.9%) 0.119 ms/op
Iteration   1: 3.173 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   1.098 ms/op
                 createUser·p0.50:   2.830 ms/op
                 createUser·p0.90:   4.059 ms/op
                 createUser·p0.95:   4.723 ms/op
                 createUser·p0.99:   9.011 ms/op
                 createUser·p0.999:  20.397 ms/op
                 createUser·p0.9999: 20.709 ms/op
                 createUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10068
  mean =      3.173 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2135 
    [ 2.500,  5.000) = 7483 
    [ 5.000,  7.500) = 299 
    [ 7.500, 10.000) = 86 
    [10.000, 12.500) = 33 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      2.830 ms/op
     p(90.0000) =      4.059 ms/op
     p(95.0000) =      4.723 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     20.397 ms/op
     p(99.9900) =     20.709 ms/op
     p(99.9990) =     20.709 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 3.071 ±(99.9%) 0.077 ms/op
Iteration   1: 2.147 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.494 ms/op
                 existUser·p0.50:   2.114 ms/op
                 existUser·p0.90:   2.630 ms/op
                 existUser·p0.95:   2.773 ms/op
                 existUser·p0.99:   3.877 ms/op
                 existUser·p0.999:  17.596 ms/op
                 existUser·p0.9999: 17.695 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 14876
  mean =      2.147 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 458 
    [ 1.250,  2.500) = 11495 
    [ 2.500,  3.750) = 2740 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 10 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      2.114 ms/op
     p(90.0000) =      2.630 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      3.877 ms/op
     p(99.9000) =     17.596 ms/op
     p(99.9900) =     17.695 ms/op
     p(99.9990) =     17.695 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.309 ±(99.9%) 0.118 ms/op
Iteration   1: 2.918 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.781 ms/op
                 getUser·p0.50:   2.765 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.953 ms/op
                 getUser·p0.99:   5.267 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 10.506 ms/op
                 getUser·p1.00:   10.617 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10975
  mean =      2.918 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 12 
    [ 1.000,  2.000) = 319 
    [ 2.000,  3.000) = 6283 
    [ 3.000,  4.000) = 3866 
    [ 4.000,  5.000) = 320 
    [ 5.000,  6.000) = 123 
    [ 6.000,  7.000) = 39 
    [ 7.000,  8.000) = 10 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.781 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      3.686 ms/op
     p(95.0000) =      3.953 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =      7.045 ms/op
     p(99.9900) =     10.506 ms/op
     p(99.9990) =     10.617 ms/op
     p(99.9999) =     10.617 ms/op
    p(100.0000) =     10.617 ms/op


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
# Warmup Iteration   1: 11.860 ±(99.9%) 0.404 ms/op
Iteration   1: 7.446 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   3.097 ms/op
                 listUser·p0.50:   7.131 ms/op
                 listUser·p0.90:   9.503 ms/op
                 listUser·p0.95:   10.932 ms/op
                 listUser·p0.99:   14.582 ms/op
                 listUser·p0.999:  20.069 ms/op
                 listUser·p0.9999: 22.807 ms/op
                 listUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4294
  mean =      7.446 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 234 
    [ 5.000,  7.500) = 2300 
    [ 7.500, 10.000) = 1438 
    [10.000, 12.500) = 226 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.097 ms/op
     p(50.0000) =      7.131 ms/op
     p(90.0000) =      9.503 ms/op
     p(95.0000) =     10.932 ms/op
     p(99.0000) =     14.582 ms/op
     p(99.9000) =     20.069 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.297          ops/ms
Client.existUser                       thrpt         10.821          ops/ms
Client.getUser                         thrpt          8.311          ops/ms
Client.listUser                        thrpt          3.386          ops/ms
Client.createUser                       avgt          3.062           ms/op
Client.existUser                        avgt          1.985           ms/op
Client.getUser                          avgt          3.209           ms/op
Client.listUser                         avgt          8.181           ms/op
Client.createUser                     sample  10068   3.173 ± 0.046   ms/op
Client.createUser:createUser·p0.00    sample          1.098           ms/op
Client.createUser:createUser·p0.50    sample          2.830           ms/op
Client.createUser:createUser·p0.90    sample          4.059           ms/op
Client.createUser:createUser·p0.95    sample          4.723           ms/op
Client.createUser:createUser·p0.99    sample          9.011           ms/op
Client.createUser:createUser·p0.999   sample         20.397           ms/op
Client.createUser:createUser·p0.9999  sample         20.709           ms/op
Client.createUser:createUser·p1.00    sample         20.709           ms/op
Client.existUser                      sample  14876   2.147 ± 0.024   ms/op
Client.existUser:existUser·p0.00      sample          0.494           ms/op
Client.existUser:existUser·p0.50      sample          2.114           ms/op
Client.existUser:existUser·p0.90      sample          2.630           ms/op
Client.existUser:existUser·p0.95      sample          2.773           ms/op
Client.existUser:existUser·p0.99      sample          3.877           ms/op
Client.existUser:existUser·p0.999     sample         17.596           ms/op
Client.existUser:existUser·p0.9999    sample         17.695           ms/op
Client.existUser:existUser·p1.00      sample         17.695           ms/op
Client.getUser                        sample  10975   2.918 ± 0.022   ms/op
Client.getUser:getUser·p0.00          sample          0.781           ms/op
Client.getUser:getUser·p0.50          sample          2.765           ms/op
Client.getUser:getUser·p0.90          sample          3.686           ms/op
Client.getUser:getUser·p0.95          sample          3.953           ms/op
Client.getUser:getUser·p0.99          sample          5.267           ms/op
Client.getUser:getUser·p0.999         sample          7.045           ms/op
Client.getUser:getUser·p0.9999        sample         10.506           ms/op
Client.getUser:getUser·p1.00          sample         10.617           ms/op
Client.listUser                       sample   4294   7.446 ± 0.099   ms/op
Client.listUser:listUser·p0.00        sample          3.097           ms/op
Client.listUser:listUser·p0.50        sample          7.131           ms/op
Client.listUser:listUser·p0.90        sample          9.503           ms/op
Client.listUser:listUser·p0.95        sample         10.932           ms/op
Client.listUser:listUser·p0.99        sample         14.582           ms/op
Client.listUser:listUser·p0.999       sample         20.069           ms/op
Client.listUser:listUser·p0.9999      sample         22.807           ms/op
Client.listUser:listUser·p1.00        sample         22.807           ms/op
