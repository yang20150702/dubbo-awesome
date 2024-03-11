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
# Warmup Iteration   1: 2.451 ops/ms
Iteration   1: 6.020 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.020 ops/ms


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
# Warmup Iteration   1: 6.236 ops/ms
Iteration   1: 12.631 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  12.631 ops/ms


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
# Warmup Iteration   1: 4.671 ops/ms
Iteration   1: 8.201 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.201 ops/ms


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
# Warmup Iteration   1: 1.971 ops/ms
Iteration   1: 3.459 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.459 ops/ms


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
# Warmup Iteration   1: 5.201 ±(99.9%) 0.049 ms/op
Iteration   1: 3.190 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.190 ms/op


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
# Warmup Iteration   1: 3.442 ±(99.9%) 0.038 ms/op
Iteration   1: 2.023 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.023 ms/op


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
# Warmup Iteration   1: 4.653 ±(99.9%) 0.064 ms/op
Iteration   1: 3.358 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.358 ms/op


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
# Warmup Iteration   1: 12.238 ±(99.9%) 0.223 ms/op
Iteration   1: 8.312 ±(99.9%) 0.069 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.312 ms/op


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
# Warmup Iteration   1: 5.093 ±(99.9%) 0.104 ms/op
Iteration   1: 2.993 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.092 ms/op
                 createUser·p0.50:   2.834 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   6.772 ms/op
                 createUser·p0.999:  9.983 ms/op
                 createUser·p0.9999: 12.598 ms/op
                 createUser·p1.00:   12.599 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10839
  mean =      2.993 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 1102 
    [ 2.500,  3.750) = 8822 
    [ 3.750,  5.000) = 734 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 41 
    [ 8.750, 10.000) = 13 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 4 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.092 ms/op
     p(50.0000) =      2.834 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      6.772 ms/op
     p(99.9000) =      9.983 ms/op
     p(99.9900) =     12.598 ms/op
     p(99.9990) =     12.599 ms/op
     p(99.9999) =     12.599 ms/op
    p(100.0000) =     12.599 ms/op


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
# Warmup Iteration   1: 3.104 ±(99.9%) 0.061 ms/op
Iteration   1: 2.004 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.400 ms/op
                 existUser·p0.50:   1.888 ms/op
                 existUser·p0.90:   2.544 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   3.723 ms/op
                 existUser·p0.999:  17.170 ms/op
                 existUser·p0.9999: 17.839 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 15942
  mean =      2.004 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 261 
    [ 1.250,  2.500) = 13871 
    [ 2.500,  3.750) = 1655 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 29 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.400 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.544 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.723 ms/op
     p(99.9000) =     17.170 ms/op
     p(99.9900) =     17.839 ms/op
     p(99.9990) =     17.859 ms/op
     p(99.9999) =     17.859 ms/op
    p(100.0000) =     17.859 ms/op


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
# Warmup Iteration   1: 4.326 ±(99.9%) 0.099 ms/op
Iteration   1: 3.058 ±(99.9%) 0.041 ms/op
                 getUser·p0.00:   0.894 ms/op
                 getUser·p0.50:   2.765 ms/op
                 getUser·p0.90:   4.076 ms/op
                 getUser·p0.95:   4.375 ms/op
                 getUser·p0.99:   5.680 ms/op
                 getUser·p0.999:  21.463 ms/op
                 getUser·p0.9999: 22.151 ms/op
                 getUser·p1.00:   22.151 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10467
  mean =      3.058 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3150 
    [ 2.500,  5.000) = 7128 
    [ 5.000,  7.500) = 156 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.894 ms/op
     p(50.0000) =      2.765 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      5.680 ms/op
     p(99.9000) =     21.463 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     22.151 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


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
# Warmup Iteration   1: 13.671 ±(99.9%) 0.468 ms/op
Iteration   1: 9.915 ±(99.9%) 0.158 ms/op
                 listUser·p0.00:   3.203 ms/op
                 listUser·p0.50:   9.519 ms/op
                 listUser·p0.90:   13.206 ms/op
                 listUser·p0.95:   14.402 ms/op
                 listUser·p0.99:   19.038 ms/op
                 listUser·p0.999:  24.462 ms/op
                 listUser·p0.9999: 25.657 ms/op
                 listUser·p1.00:   25.657 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3198
  mean =      9.915 ±(99.9%) 0.158 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 35 
    [ 5.000,  7.500) = 478 
    [ 7.500, 10.000) = 1358 
    [10.000, 12.500) = 844 
    [12.500, 15.000) = 344 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 72 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.203 ms/op
     p(50.0000) =      9.519 ms/op
     p(90.0000) =     13.206 ms/op
     p(95.0000) =     14.402 ms/op
     p(99.0000) =     19.038 ms/op
     p(99.9000) =     24.462 ms/op
     p(99.9900) =     25.657 ms/op
     p(99.9990) =     25.657 ms/op
     p(99.9999) =     25.657 ms/op
    p(100.0000) =     25.657 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.020          ops/ms
Client.existUser                       thrpt         12.631          ops/ms
Client.getUser                         thrpt          8.201          ops/ms
Client.listUser                        thrpt          3.459          ops/ms
Client.createUser                       avgt          3.190           ms/op
Client.existUser                        avgt          2.023           ms/op
Client.getUser                          avgt          3.358           ms/op
Client.listUser                         avgt          8.312           ms/op
Client.createUser                     sample  10839   2.993 ± 0.023   ms/op
Client.createUser:createUser·p0.00    sample          1.092           ms/op
Client.createUser:createUser·p0.50    sample          2.834           ms/op
Client.createUser:createUser·p0.90    sample          3.625           ms/op
Client.createUser:createUser·p0.95    sample          3.949           ms/op
Client.createUser:createUser·p0.99    sample          6.772           ms/op
Client.createUser:createUser·p0.999   sample          9.983           ms/op
Client.createUser:createUser·p0.9999  sample         12.598           ms/op
Client.createUser:createUser·p1.00    sample         12.599           ms/op
Client.existUser                      sample  15942   2.004 ± 0.022   ms/op
Client.existUser:existUser·p0.00      sample          0.400           ms/op
Client.existUser:existUser·p0.50      sample          1.888           ms/op
Client.existUser:existUser·p0.90      sample          2.544           ms/op
Client.existUser:existUser·p0.95      sample          2.744           ms/op
Client.existUser:existUser·p0.99      sample          3.723           ms/op
Client.existUser:existUser·p0.999     sample         17.170           ms/op
Client.existUser:existUser·p0.9999    sample         17.839           ms/op
Client.existUser:existUser·p1.00      sample         17.859           ms/op
Client.getUser                        sample  10467   3.058 ± 0.041   ms/op
Client.getUser:getUser·p0.00          sample          0.894           ms/op
Client.getUser:getUser·p0.50          sample          2.765           ms/op
Client.getUser:getUser·p0.90          sample          4.076           ms/op
Client.getUser:getUser·p0.95          sample          4.375           ms/op
Client.getUser:getUser·p0.99          sample          5.680           ms/op
Client.getUser:getUser·p0.999         sample         21.463           ms/op
Client.getUser:getUser·p0.9999        sample         22.151           ms/op
Client.getUser:getUser·p1.00          sample         22.151           ms/op
Client.listUser                       sample   3198   9.915 ± 0.158   ms/op
Client.listUser:listUser·p0.00        sample          3.203           ms/op
Client.listUser:listUser·p0.50        sample          9.519           ms/op
Client.listUser:listUser·p0.90        sample         13.206           ms/op
Client.listUser:listUser·p0.95        sample         14.402           ms/op
Client.listUser:listUser·p0.99        sample         19.038           ms/op
Client.listUser:listUser·p0.999       sample         24.462           ms/op
Client.listUser:listUser·p0.9999      sample         25.657           ms/op
Client.listUser:listUser·p1.00        sample         25.657           ms/op
