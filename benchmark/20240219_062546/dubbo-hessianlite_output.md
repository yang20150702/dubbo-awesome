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
# Warmup Iteration   1: 2.066 ops/ms
Iteration   1: 5.845 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.845 ops/ms


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
# Warmup Iteration   1: 6.527 ops/ms
Iteration   1: 12.764 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.764 ops/ms


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
# Warmup Iteration   1: 4.484 ops/ms
Iteration   1: 8.566 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.566 ops/ms


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
# Warmup Iteration   1: 2.156 ops/ms
Iteration   1: 3.664 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.664 ops/ms


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
# Warmup Iteration   1: 5.279 ±(99.9%) 0.069 ms/op
Iteration   1: 3.271 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.271 ms/op


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
# Warmup Iteration   1: 3.385 ±(99.9%) 0.039 ms/op
Iteration   1: 1.913 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.913 ms/op


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
# Warmup Iteration   1: 4.681 ±(99.9%) 0.058 ms/op
Iteration   1: 3.019 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.019 ms/op


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
# Warmup Iteration   1: 12.755 ±(99.9%) 0.219 ms/op
Iteration   1: 7.190 ±(99.9%) 0.074 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.190 ms/op


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
# Warmup Iteration   1: 4.844 ±(99.9%) 0.100 ms/op
Iteration   1: 3.025 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   1.284 ms/op
                 createUser·p0.50:   2.826 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.129 ms/op
                 createUser·p0.99:   7.476 ms/op
                 createUser·p0.999:  12.075 ms/op
                 createUser·p0.9999: 12.156 ms/op
                 createUser·p1.00:   12.157 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10641
  mean =      3.025 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 1228 
    [ 2.500,  3.750) = 8352 
    [ 3.750,  5.000) = 772 
    [ 5.000,  6.250) = 146 
    [ 6.250,  7.500) = 37 
    [ 7.500,  8.750) = 33 
    [ 8.750, 10.000) = 59 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      2.826 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.129 ms/op
     p(99.0000) =      7.476 ms/op
     p(99.9000) =     12.075 ms/op
     p(99.9900) =     12.156 ms/op
     p(99.9990) =     12.157 ms/op
     p(99.9999) =     12.157 ms/op
    p(100.0000) =     12.157 ms/op


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
# Warmup Iteration   1: 3.035 ±(99.9%) 0.082 ms/op
Iteration   1: 1.796 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.560 ms/op
                 existUser·p0.50:   1.769 ms/op
                 existUser·p0.90:   2.290 ms/op
                 existUser·p0.95:   2.503 ms/op
                 existUser·p0.99:   2.912 ms/op
                 existUser·p0.999:  3.912 ms/op
                 existUser·p0.9999: 4.532 ms/op
                 existUser·p1.00:   4.596 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17822
  mean =      1.796 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 102 
    [1.000, 1.500) = 4043 
    [1.500, 2.000) = 9174 
    [2.000, 2.500) = 3597 
    [2.500, 3.000) = 766 
    [3.000, 3.500) = 71 
    [3.500, 4.000) = 65 
    [4.000, 4.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.560 ms/op
     p(50.0000) =      1.769 ms/op
     p(90.0000) =      2.290 ms/op
     p(95.0000) =      2.503 ms/op
     p(99.0000) =      2.912 ms/op
     p(99.9000) =      3.912 ms/op
     p(99.9900) =      4.532 ms/op
     p(99.9990) =      4.596 ms/op
     p(99.9999) =      4.596 ms/op
    p(100.0000) =      4.596 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.107 ms/op
Iteration   1: 2.807 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   1.155 ms/op
                 getUser·p0.50:   2.523 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.791 ms/op
                 getUser·p0.999:  21.398 ms/op
                 getUser·p0.9999: 22.011 ms/op
                 getUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11396
  mean =      2.807 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5520 
    [ 2.500,  5.000) = 5713 
    [ 5.000,  7.500) = 93 
    [ 7.500, 10.000) = 37 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.155 ms/op
     p(50.0000) =      2.523 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     21.398 ms/op
     p(99.9900) =     22.011 ms/op
     p(99.9990) =     22.020 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


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
# Warmup Iteration   1: 13.205 ±(99.9%) 0.412 ms/op
Iteration   1: 7.808 ±(99.9%) 0.103 ms/op
                 listUser·p0.00:   3.305 ms/op
                 listUser·p0.50:   7.496 ms/op
                 listUser·p0.90:   10.404 ms/op
                 listUser·p0.95:   11.583 ms/op
                 listUser·p0.99:   13.926 ms/op
                 listUser·p0.999:  16.301 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4100
  mean =      7.808 ±(99.9%) 0.103 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 196 
    [ 5.000,  7.500) = 1858 
    [ 7.500, 10.000) = 1489 
    [10.000, 12.500) = 446 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.305 ms/op
     p(50.0000) =      7.496 ms/op
     p(90.0000) =     10.404 ms/op
     p(95.0000) =     11.583 ms/op
     p(99.0000) =     13.926 ms/op
     p(99.9000) =     16.301 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     20.414 ms/op
     p(99.9999) =     20.414 ms/op
    p(100.0000) =     20.414 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.845          ops/ms
Client.existUser                       thrpt         12.764          ops/ms
Client.getUser                         thrpt          8.566          ops/ms
Client.listUser                        thrpt          3.664          ops/ms
Client.createUser                       avgt          3.271           ms/op
Client.existUser                        avgt          1.913           ms/op
Client.getUser                          avgt          3.019           ms/op
Client.listUser                         avgt          7.190           ms/op
Client.createUser                     sample  10641   3.025 ± 0.028   ms/op
Client.createUser:createUser·p0.00    sample          1.284           ms/op
Client.createUser:createUser·p0.50    sample          2.826           ms/op
Client.createUser:createUser·p0.90    sample          3.748           ms/op
Client.createUser:createUser·p0.95    sample          4.129           ms/op
Client.createUser:createUser·p0.99    sample          7.476           ms/op
Client.createUser:createUser·p0.999   sample         12.075           ms/op
Client.createUser:createUser·p0.9999  sample         12.156           ms/op
Client.createUser:createUser·p1.00    sample         12.157           ms/op
Client.existUser                      sample  17822   1.796 ± 0.010   ms/op
Client.existUser:existUser·p0.00      sample          0.560           ms/op
Client.existUser:existUser·p0.50      sample          1.769           ms/op
Client.existUser:existUser·p0.90      sample          2.290           ms/op
Client.existUser:existUser·p0.95      sample          2.503           ms/op
Client.existUser:existUser·p0.99      sample          2.912           ms/op
Client.existUser:existUser·p0.999     sample          3.912           ms/op
Client.existUser:existUser·p0.9999    sample          4.532           ms/op
Client.existUser:existUser·p1.00      sample          4.596           ms/op
Client.getUser                        sample  11396   2.807 ± 0.038   ms/op
Client.getUser:getUser·p0.00          sample          1.155           ms/op
Client.getUser:getUser·p0.50          sample          2.523           ms/op
Client.getUser:getUser·p0.90          sample          3.629           ms/op
Client.getUser:getUser·p0.95          sample          3.932           ms/op
Client.getUser:getUser·p0.99          sample          6.791           ms/op
Client.getUser:getUser·p0.999         sample         21.398           ms/op
Client.getUser:getUser·p0.9999        sample         22.011           ms/op
Client.getUser:getUser·p1.00          sample         22.020           ms/op
Client.listUser                       sample   4100   7.808 ± 0.103   ms/op
Client.listUser:listUser·p0.00        sample          3.305           ms/op
Client.listUser:listUser·p0.50        sample          7.496           ms/op
Client.listUser:listUser·p0.90        sample         10.404           ms/op
Client.listUser:listUser·p0.95        sample         11.583           ms/op
Client.listUser:listUser·p0.99        sample         13.926           ms/op
Client.listUser:listUser·p0.999       sample         16.301           ms/op
Client.listUser:listUser·p0.9999      sample         20.414           ms/op
Client.listUser:listUser·p1.00        sample         20.414           ms/op
