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
# Warmup Iteration   1: 2.467 ops/ms
Iteration   1: 5.331 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.331 ops/ms


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
# Warmup Iteration   1: 6.514 ops/ms
Iteration   1: 11.785 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  11.785 ops/ms


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
# Warmup Iteration   1: 4.059 ops/ms
Iteration   1: 8.671 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.671 ops/ms


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
# Warmup Iteration   1: 2.270 ops/ms
Iteration   1: 3.433 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.433 ops/ms


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
# Warmup Iteration   1: 6.483 ±(99.9%) 0.090 ms/op
Iteration   1: 3.391 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.391 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.039 ms/op
Iteration   1: 1.954 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.954 ms/op


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
# Warmup Iteration   1: 5.355 ±(99.9%) 0.087 ms/op
Iteration   1: 3.026 ±(99.9%) 0.030 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.026 ms/op


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
# Warmup Iteration   1: 12.573 ±(99.9%) 0.248 ms/op
Iteration   1: 8.974 ±(99.9%) 0.101 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.974 ms/op


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
# Warmup Iteration   1: 5.778 ±(99.9%) 0.128 ms/op
Iteration   1: 3.444 ±(99.9%) 0.035 ms/op
                 createUser·p0.00:   1.300 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   5.015 ms/op
                 createUser·p0.99:   6.701 ms/op
                 createUser·p0.999:  15.106 ms/op
                 createUser·p0.9999: 15.204 ms/op
                 createUser·p1.00:   15.204 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9296
  mean =      3.444 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 443 
    [ 2.500,  3.750) = 6937 
    [ 3.750,  5.000) = 1446 
    [ 5.000,  6.250) = 317 
    [ 6.250,  7.500) = 117 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 16 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.300 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      5.015 ms/op
     p(99.0000) =      6.701 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     15.204 ms/op
     p(99.9990) =     15.204 ms/op
     p(99.9999) =     15.204 ms/op
    p(100.0000) =     15.204 ms/op


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
# Warmup Iteration   1: 3.327 ±(99.9%) 0.090 ms/op
Iteration   1: 2.115 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.568 ms/op
                 existUser·p0.50:   1.937 ms/op
                 existUser·p0.90:   2.707 ms/op
                 existUser·p0.95:   3.015 ms/op
                 existUser·p0.99:   3.477 ms/op
                 existUser·p0.999:  19.792 ms/op
                 existUser·p0.9999: 20.312 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15212
  mean =      2.115 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12704 
    [ 2.500,  5.000) = 2426 
    [ 5.000,  7.500) = 17 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 60 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      1.937 ms/op
     p(90.0000) =      2.707 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      3.477 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     20.312 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


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
# Warmup Iteration   1: 5.036 ±(99.9%) 0.135 ms/op
Iteration   1: 3.329 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   1.280 ms/op
                 getUser·p0.50:   3.260 ms/op
                 getUser·p0.90:   4.538 ms/op
                 getUser·p0.95:   4.874 ms/op
                 getUser·p0.99:   5.818 ms/op
                 getUser·p0.999:  7.321 ms/op
                 getUser·p0.9999: 9.159 ms/op
                 getUser·p1.00:   9.159 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 9593
  mean =      3.329 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 16 
    [ 1.500,  2.000) = 259 
    [ 2.000,  2.500) = 1825 
    [ 2.500,  3.000) = 1804 
    [ 3.000,  3.500) = 1884 
    [ 3.500,  4.000) = 1533 
    [ 4.000,  4.500) = 1218 
    [ 4.500,  5.000) = 685 
    [ 5.000,  5.500) = 240 
    [ 5.500,  6.000) = 62 
    [ 6.000,  6.500) = 21 
    [ 6.500,  7.000) = 23 
    [ 7.000,  7.500) = 17 
    [ 7.500,  8.000) = 4 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 1 
    [ 9.000,  9.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.280 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      5.818 ms/op
     p(99.9000) =      7.321 ms/op
     p(99.9900) =      9.159 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.787 ±(99.9%) 0.379 ms/op
Iteration   1: 8.512 ±(99.9%) 0.115 ms/op
                 listUser·p0.00:   2.232 ms/op
                 listUser·p0.50:   8.184 ms/op
                 listUser·p0.90:   11.354 ms/op
                 listUser·p0.95:   12.075 ms/op
                 listUser·p0.99:   14.506 ms/op
                 listUser·p0.999:  19.268 ms/op
                 listUser·p0.9999: 19.923 ms/op
                 listUser·p1.00:   19.923 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3753
  mean =      8.512 ±(99.9%) 0.115 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 3 
    [ 2.500,  3.750) = 35 
    [ 3.750,  5.000) = 72 
    [ 5.000,  6.250) = 264 
    [ 6.250,  7.500) = 867 
    [ 7.500,  8.750) = 1062 
    [ 8.750, 10.000) = 596 
    [10.000, 11.250) = 460 
    [11.250, 12.500) = 269 
    [12.500, 13.750) = 74 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 13 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.232 ms/op
     p(50.0000) =      8.184 ms/op
     p(90.0000) =     11.354 ms/op
     p(95.0000) =     12.075 ms/op
     p(99.0000) =     14.506 ms/op
     p(99.9000) =     19.268 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     19.923 ms/op
     p(99.9999) =     19.923 ms/op
    p(100.0000) =     19.923 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.331          ops/ms
Client.existUser                       thrpt         11.785          ops/ms
Client.getUser                         thrpt          8.671          ops/ms
Client.listUser                        thrpt          3.433          ops/ms
Client.createUser                       avgt          3.391           ms/op
Client.existUser                        avgt          1.954           ms/op
Client.getUser                          avgt          3.026           ms/op
Client.listUser                         avgt          8.974           ms/op
Client.createUser                     sample   9296   3.444 ± 0.035   ms/op
Client.createUser:createUser·p0.00    sample          1.300           ms/op
Client.createUser:createUser·p0.50    sample          3.244           ms/op
Client.createUser:createUser·p0.90    sample          4.383           ms/op
Client.createUser:createUser·p0.95    sample          5.015           ms/op
Client.createUser:createUser·p0.99    sample          6.701           ms/op
Client.createUser:createUser·p0.999   sample         15.106           ms/op
Client.createUser:createUser·p0.9999  sample         15.204           ms/op
Client.createUser:createUser·p1.00    sample         15.204           ms/op
Client.existUser                      sample  15212   2.115 ± 0.033   ms/op
Client.existUser:existUser·p0.00      sample          0.568           ms/op
Client.existUser:existUser·p0.50      sample          1.937           ms/op
Client.existUser:existUser·p0.90      sample          2.707           ms/op
Client.existUser:existUser·p0.95      sample          3.015           ms/op
Client.existUser:existUser·p0.99      sample          3.477           ms/op
Client.existUser:existUser·p0.999     sample         19.792           ms/op
Client.existUser:existUser·p0.9999    sample         20.312           ms/op
Client.existUser:existUser·p1.00      sample         20.414           ms/op
Client.getUser                        sample   9593   3.329 ± 0.031   ms/op
Client.getUser:getUser·p0.00          sample          1.280           ms/op
Client.getUser:getUser·p0.50          sample          3.260           ms/op
Client.getUser:getUser·p0.90          sample          4.538           ms/op
Client.getUser:getUser·p0.95          sample          4.874           ms/op
Client.getUser:getUser·p0.99          sample          5.818           ms/op
Client.getUser:getUser·p0.999         sample          7.321           ms/op
Client.getUser:getUser·p0.9999        sample          9.159           ms/op
Client.getUser:getUser·p1.00          sample          9.159           ms/op
Client.listUser                       sample   3753   8.512 ± 0.115   ms/op
Client.listUser:listUser·p0.00        sample          2.232           ms/op
Client.listUser:listUser·p0.50        sample          8.184           ms/op
Client.listUser:listUser·p0.90        sample         11.354           ms/op
Client.listUser:listUser·p0.95        sample         12.075           ms/op
Client.listUser:listUser·p0.99        sample         14.506           ms/op
Client.listUser:listUser·p0.999       sample         19.268           ms/op
Client.listUser:listUser·p0.9999      sample         19.923           ms/op
Client.listUser:listUser·p1.00        sample         19.923           ms/op
