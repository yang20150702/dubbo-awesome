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
# Warmup Iteration   1: 2.033 ops/ms
Iteration   1: 5.483 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  5.483 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.054 ops/ms
Iteration   1: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  10.498 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 3.911 ops/ms
Iteration   1: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.105 ops/ms


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
# Warmup Iteration   1: 2.248 ops/ms
Iteration   1: 3.631 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.631 ops/ms


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
# Warmup Iteration   1: 5.937 ±(99.9%) 0.153 ms/op
Iteration   1: 3.663 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.663 ms/op


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
# Warmup Iteration   1: 4.184 ±(99.9%) 0.047 ms/op
Iteration   1: 2.266 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.266 ms/op


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
# Warmup Iteration   1: 4.988 ±(99.9%) 0.050 ms/op
Iteration   1: 3.021 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.021 ms/op


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
# Warmup Iteration   1: 12.686 ±(99.9%) 0.294 ms/op
Iteration   1: 8.976 ±(99.9%) 0.080 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.976 ms/op


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
# Warmup Iteration   1: 5.438 ±(99.9%) 0.135 ms/op
Iteration   1: 3.266 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.997 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   4.100 ms/op
                 createUser·p0.95:   4.735 ms/op
                 createUser·p0.99:   10.341 ms/op
                 createUser·p0.999:  15.417 ms/op
                 createUser·p0.9999: 17.990 ms/op
                 createUser·p1.00:   17.990 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 9785
  mean =      3.266 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1511 
    [ 2.500,  3.750) = 6822 
    [ 3.750,  5.000) = 1043 
    [ 5.000,  6.250) = 105 
    [ 6.250,  7.500) = 96 
    [ 7.500,  8.750) = 19 
    [ 8.750, 10.000) = 52 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.997 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      4.100 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =     10.341 ms/op
     p(99.9000) =     15.417 ms/op
     p(99.9900) =     17.990 ms/op
     p(99.9990) =     17.990 ms/op
     p(99.9999) =     17.990 ms/op
    p(100.0000) =     17.990 ms/op


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
# Warmup Iteration   1: 3.260 ±(99.9%) 0.076 ms/op
Iteration   1: 1.962 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.640 ms/op
                 existUser·p0.50:   1.847 ms/op
                 existUser·p0.90:   2.507 ms/op
                 existUser·p0.95:   2.724 ms/op
                 existUser·p0.99:   4.113 ms/op
                 existUser·p0.999:  18.921 ms/op
                 existUser·p0.9999: 19.562 ms/op
                 existUser·p1.00:   19.562 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16295
  mean =      1.962 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 402 
    [ 1.250,  2.500) = 14232 
    [ 2.500,  3.750) = 1453 
    [ 3.750,  5.000) = 151 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      1.847 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      4.113 ms/op
     p(99.9000) =     18.921 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     19.562 ms/op
     p(99.9999) =     19.562 ms/op
    p(100.0000) =     19.562 ms/op


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
# Warmup Iteration   1: 4.848 ±(99.9%) 0.130 ms/op
Iteration   1: 2.951 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.712 ms/op
                 getUser·p0.50:   2.916 ms/op
                 getUser·p0.90:   3.748 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   4.807 ms/op
                 getUser·p0.999:  7.458 ms/op
                 getUser·p0.9999: 9.354 ms/op
                 getUser·p1.00:   9.454 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10909
  mean =      2.951 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 7 
    [ 1.000,  2.000) = 360 
    [ 2.000,  3.000) = 5736 
    [ 3.000,  4.000) = 4238 
    [ 4.000,  5.000) = 470 
    [ 5.000,  6.000) = 59 
    [ 6.000,  7.000) = 17 
    [ 7.000,  8.000) = 20 
    [ 8.000,  9.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.712 ms/op
     p(50.0000) =      2.916 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.018 ms/op
     p(99.0000) =      4.807 ms/op
     p(99.9000) =      7.458 ms/op
     p(99.9900) =      9.354 ms/op
     p(99.9990) =      9.454 ms/op
     p(99.9999) =      9.454 ms/op
    p(100.0000) =      9.454 ms/op


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
# Warmup Iteration   1: 12.645 ±(99.9%) 0.485 ms/op
Iteration   1: 8.811 ±(99.9%) 0.134 ms/op
                 listUser·p0.00:   3.236 ms/op
                 listUser·p0.50:   8.503 ms/op
                 listUser·p0.90:   11.190 ms/op
                 listUser·p0.95:   12.337 ms/op
                 listUser·p0.99:   17.715 ms/op
                 listUser·p0.999:  28.003 ms/op
                 listUser·p0.9999: 28.574 ms/op
                 listUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3633
  mean =      8.811 ±(99.9%) 0.134 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 41 
    [ 5.000,  7.500) = 970 
    [ 7.500, 10.000) = 1789 
    [10.000, 12.500) = 670 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      3.236 ms/op
     p(50.0000) =      8.503 ms/op
     p(90.0000) =     11.190 ms/op
     p(95.0000) =     12.337 ms/op
     p(99.0000) =     17.715 ms/op
     p(99.9000) =     28.003 ms/op
     p(99.9900) =     28.574 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          5.483          ops/ms
Client.existUser                       thrpt         10.498          ops/ms
Client.getUser                         thrpt          8.105          ops/ms
Client.listUser                        thrpt          3.631          ops/ms
Client.createUser                       avgt          3.663           ms/op
Client.existUser                        avgt          2.266           ms/op
Client.getUser                          avgt          3.021           ms/op
Client.listUser                         avgt          8.976           ms/op
Client.createUser                     sample   9785   3.266 ± 0.046   ms/op
Client.createUser:createUser·p0.00    sample          0.997           ms/op
Client.createUser:createUser·p0.50    sample          2.998           ms/op
Client.createUser:createUser·p0.90    sample          4.100           ms/op
Client.createUser:createUser·p0.95    sample          4.735           ms/op
Client.createUser:createUser·p0.99    sample         10.341           ms/op
Client.createUser:createUser·p0.999   sample         15.417           ms/op
Client.createUser:createUser·p0.9999  sample         17.990           ms/op
Client.createUser:createUser·p1.00    sample         17.990           ms/op
Client.existUser                      sample  16295   1.962 ± 0.023   ms/op
Client.existUser:existUser·p0.00      sample          0.640           ms/op
Client.existUser:existUser·p0.50      sample          1.847           ms/op
Client.existUser:existUser·p0.90      sample          2.507           ms/op
Client.existUser:existUser·p0.95      sample          2.724           ms/op
Client.existUser:existUser·p0.99      sample          4.113           ms/op
Client.existUser:existUser·p0.999     sample         18.921           ms/op
Client.existUser:existUser·p0.9999    sample         19.562           ms/op
Client.existUser:existUser·p1.00      sample         19.562           ms/op
Client.getUser                        sample  10909   2.951 ± 0.021   ms/op
Client.getUser:getUser·p0.00          sample          0.712           ms/op
Client.getUser:getUser·p0.50          sample          2.916           ms/op
Client.getUser:getUser·p0.90          sample          3.748           ms/op
Client.getUser:getUser·p0.95          sample          4.018           ms/op
Client.getUser:getUser·p0.99          sample          4.807           ms/op
Client.getUser:getUser·p0.999         sample          7.458           ms/op
Client.getUser:getUser·p0.9999        sample          9.354           ms/op
Client.getUser:getUser·p1.00          sample          9.454           ms/op
Client.listUser                       sample   3633   8.811 ± 0.134   ms/op
Client.listUser:listUser·p0.00        sample          3.236           ms/op
Client.listUser:listUser·p0.50        sample          8.503           ms/op
Client.listUser:listUser·p0.90        sample         11.190           ms/op
Client.listUser:listUser·p0.95        sample         12.337           ms/op
Client.listUser:listUser·p0.99        sample         17.715           ms/op
Client.listUser:listUser·p0.999       sample         28.003           ms/op
Client.listUser:listUser·p0.9999      sample         28.574           ms/op
Client.listUser:listUser·p1.00        sample         28.574           ms/op
