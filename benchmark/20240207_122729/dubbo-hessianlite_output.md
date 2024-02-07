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
# Warmup Iteration   1: 2.219 ops/ms
Iteration   1: 5.988 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.988 ops/ms


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
# Warmup Iteration   1: 6.286 ops/ms
Iteration   1: 13.345 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.345 ops/ms


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
# Warmup Iteration   1: 4.617 ops/ms
Iteration   1: 8.030 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.030 ops/ms


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
# Warmup Iteration   1: 2.208 ops/ms
Iteration   1: 3.200 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.200 ops/ms


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
# Warmup Iteration   1: 5.692 ±(99.9%) 0.080 ms/op
Iteration   1: 3.168 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.168 ms/op


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
# Warmup Iteration   1: 3.044 ±(99.9%) 0.038 ms/op
Iteration   1: 1.809 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.809 ms/op


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
# Warmup Iteration   1: 5.423 ±(99.9%) 0.072 ms/op
Iteration   1: 3.336 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.336 ms/op


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
# Warmup Iteration   1: 12.261 ±(99.9%) 0.233 ms/op
Iteration   1: 8.893 ±(99.9%) 0.082 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.893 ms/op


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
# Warmup Iteration   1: 5.151 ±(99.9%) 0.117 ms/op
Iteration   1: 2.939 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   1.245 ms/op
                 createUser·p0.50:   2.740 ms/op
                 createUser·p0.90:   3.932 ms/op
                 createUser·p0.95:   4.850 ms/op
                 createUser·p0.99:   7.037 ms/op
                 createUser·p0.999:  9.961 ms/op
                 createUser·p0.9999: 13.756 ms/op
                 createUser·p1.00:   13.943 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10903
  mean =      2.939 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 3577 
    [ 2.500,  3.750) = 6047 
    [ 3.750,  5.000) = 897 
    [ 5.000,  6.250) = 207 
    [ 6.250,  7.500) = 89 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 5 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.245 ms/op
     p(50.0000) =      2.740 ms/op
     p(90.0000) =      3.932 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      7.037 ms/op
     p(99.9000) =      9.961 ms/op
     p(99.9900) =     13.756 ms/op
     p(99.9990) =     13.943 ms/op
     p(99.9999) =     13.943 ms/op
    p(100.0000) =     13.943 ms/op


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
# Warmup Iteration   1: 2.882 ±(99.9%) 0.071 ms/op
Iteration   1: 1.629 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   1.597 ms/op
                 existUser·p0.90:   1.888 ms/op
                 existUser·p0.95:   2.097 ms/op
                 existUser·p0.99:   2.490 ms/op
                 existUser·p0.999:  5.385 ms/op
                 existUser·p0.9999: 8.356 ms/op
                 existUser·p1.00:   8.356 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 19621
  mean =      1.629 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 96 
    [1.000, 1.500) = 6088 
    [1.500, 2.000) = 12127 
    [2.000, 2.500) = 1120 
    [2.500, 3.000) = 72 
    [3.000, 3.500) = 5 
    [3.500, 4.000) = 1 
    [4.000, 4.500) = 45 
    [4.500, 5.000) = 34 
    [5.000, 5.500) = 23 
    [5.500, 6.000) = 2 
    [6.000, 6.500) = 0 
    [6.500, 7.000) = 0 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.597 ms/op
     p(90.0000) =      1.888 ms/op
     p(95.0000) =      2.097 ms/op
     p(99.0000) =      2.490 ms/op
     p(99.9000) =      5.385 ms/op
     p(99.9900) =      8.356 ms/op
     p(99.9990) =      8.356 ms/op
     p(99.9999) =      8.356 ms/op
    p(100.0000) =      8.356 ms/op


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
# Warmup Iteration   1: 4.629 ±(99.9%) 0.116 ms/op
Iteration   1: 2.984 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.979 ms/op
                 getUser·p0.50:   2.859 ms/op
                 getUser·p0.90:   3.797 ms/op
                 getUser·p0.95:   4.141 ms/op
                 getUser·p0.99:   5.423 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 9.978 ms/op
                 getUser·p1.00:   9.978 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10704
  mean =      2.984 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 327 
    [ 2.000,  3.000) = 5994 
    [ 3.000,  4.000) = 3658 
    [ 4.000,  5.000) = 573 
    [ 5.000,  6.000) = 74 
    [ 6.000,  7.000) = 37 
    [ 7.000,  8.000) = 8 
    [ 8.000,  9.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.141 ms/op
     p(99.0000) =      5.423 ms/op
     p(99.9000) =      9.912 ms/op
     p(99.9900) =      9.978 ms/op
     p(99.9990) =      9.978 ms/op
     p(99.9999) =      9.978 ms/op
    p(100.0000) =      9.978 ms/op


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
# Warmup Iteration   1: 12.597 ±(99.9%) 0.498 ms/op
Iteration   1: 8.909 ±(99.9%) 0.138 ms/op
                 listUser·p0.00:   2.298 ms/op
                 listUser·p0.50:   8.569 ms/op
                 listUser·p0.90:   11.895 ms/op
                 listUser·p0.95:   12.894 ms/op
                 listUser·p0.99:   16.910 ms/op
                 listUser·p0.999:  27.604 ms/op
                 listUser·p0.9999: 53.608 ms/op
                 listUser·p1.00:   53.608 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3594
  mean =      8.909 ±(99.9%) 0.138 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 66 
    [ 5.000, 10.000) = 2593 
    [10.000, 15.000) = 876 
    [15.000, 20.000) = 49 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.298 ms/op
     p(50.0000) =      8.569 ms/op
     p(90.0000) =     11.895 ms/op
     p(95.0000) =     12.894 ms/op
     p(99.0000) =     16.910 ms/op
     p(99.9000) =     27.604 ms/op
     p(99.9900) =     53.608 ms/op
     p(99.9990) =     53.608 ms/op
     p(99.9999) =     53.608 ms/op
    p(100.0000) =     53.608 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.988          ops/ms
Client.existUser                       thrpt         13.345          ops/ms
Client.getUser                         thrpt          8.030          ops/ms
Client.listUser                        thrpt          3.200          ops/ms
Client.createUser                       avgt          3.168           ms/op
Client.existUser                        avgt          1.809           ms/op
Client.getUser                          avgt          3.336           ms/op
Client.listUser                         avgt          8.893           ms/op
Client.createUser                     sample  10903   2.939 ± 0.031   ms/op
Client.createUser:createUser·p0.00    sample          1.245           ms/op
Client.createUser:createUser·p0.50    sample          2.740           ms/op
Client.createUser:createUser·p0.90    sample          3.932           ms/op
Client.createUser:createUser·p0.95    sample          4.850           ms/op
Client.createUser:createUser·p0.99    sample          7.037           ms/op
Client.createUser:createUser·p0.999   sample          9.961           ms/op
Client.createUser:createUser·p0.9999  sample         13.756           ms/op
Client.createUser:createUser·p1.00    sample         13.943           ms/op
Client.existUser                      sample  19621   1.629 ± 0.008   ms/op
Client.existUser:existUser·p0.00      sample          0.532           ms/op
Client.existUser:existUser·p0.50      sample          1.597           ms/op
Client.existUser:existUser·p0.90      sample          1.888           ms/op
Client.existUser:existUser·p0.95      sample          2.097           ms/op
Client.existUser:existUser·p0.99      sample          2.490           ms/op
Client.existUser:existUser·p0.999     sample          5.385           ms/op
Client.existUser:existUser·p0.9999    sample          8.356           ms/op
Client.existUser:existUser·p1.00      sample          8.356           ms/op
Client.getUser                        sample  10704   2.984 ± 0.025   ms/op
Client.getUser:getUser·p0.00          sample          0.979           ms/op
Client.getUser:getUser·p0.50          sample          2.859           ms/op
Client.getUser:getUser·p0.90          sample          3.797           ms/op
Client.getUser:getUser·p0.95          sample          4.141           ms/op
Client.getUser:getUser·p0.99          sample          5.423           ms/op
Client.getUser:getUser·p0.999         sample          9.912           ms/op
Client.getUser:getUser·p0.9999        sample          9.978           ms/op
Client.getUser:getUser·p1.00          sample          9.978           ms/op
Client.listUser                       sample   3594   8.909 ± 0.138   ms/op
Client.listUser:listUser·p0.00        sample          2.298           ms/op
Client.listUser:listUser·p0.50        sample          8.569           ms/op
Client.listUser:listUser·p0.90        sample         11.895           ms/op
Client.listUser:listUser·p0.95        sample         12.894           ms/op
Client.listUser:listUser·p0.99        sample         16.910           ms/op
Client.listUser:listUser·p0.999       sample         27.604           ms/op
Client.listUser:listUser·p0.9999      sample         53.608           ms/op
Client.listUser:listUser·p1.00        sample         53.608           ms/op
