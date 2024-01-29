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
# Warmup Iteration   1: 2.266 ops/ms
Iteration   1: 6.392 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.392 ops/ms


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
# Warmup Iteration   1: 6.207 ops/ms
Iteration   1: 14.157 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.157 ops/ms


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
# Warmup Iteration   1: 4.096 ops/ms
Iteration   1: 8.403 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.403 ops/ms


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
# Warmup Iteration   1: 2.058 ops/ms
Iteration   1: 3.649 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.649 ops/ms


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
# Warmup Iteration   1: 5.237 ±(99.9%) 0.091 ms/op
Iteration   1: 2.959 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.959 ms/op


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
# Warmup Iteration   1: 3.075 ±(99.9%) 0.031 ms/op
Iteration   1: 2.031 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  2.031 ms/op


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.044 ms/op
Iteration   1: 3.029 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.029 ms/op


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
# Warmup Iteration   1: 13.049 ±(99.9%) 0.225 ms/op
Iteration   1: 8.509 ±(99.9%) 0.164 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  8.509 ms/op


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
# Warmup Iteration   1: 5.102 ±(99.9%) 0.124 ms/op
Iteration   1: 2.813 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.986 ms/op
                 createUser·p0.50:   2.748 ms/op
                 createUser·p0.90:   3.305 ms/op
                 createUser·p0.95:   3.592 ms/op
                 createUser·p0.99:   5.354 ms/op
                 createUser·p0.999:  17.236 ms/op
                 createUser·p0.9999: 17.618 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11355
  mean =      2.813 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 57 
    [ 1.250,  2.500) = 2977 
    [ 2.500,  3.750) = 7887 
    [ 3.750,  5.000) = 313 
    [ 5.000,  6.250) = 79 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.986 ms/op
     p(50.0000) =      2.748 ms/op
     p(90.0000) =      3.305 ms/op
     p(95.0000) =      3.592 ms/op
     p(99.0000) =      5.354 ms/op
     p(99.9000) =     17.236 ms/op
     p(99.9900) =     17.618 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.071 ms/op
Iteration   1: 1.829 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.642 ms/op
                 existUser·p0.50:   1.751 ms/op
                 existUser·p0.90:   2.216 ms/op
                 existUser·p0.95:   2.351 ms/op
                 existUser·p0.99:   2.860 ms/op
                 existUser·p0.999:  18.153 ms/op
                 existUser·p0.9999: 18.832 ms/op
                 existUser·p1.00:   18.907 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 17684
  mean =      1.829 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 690 
    [ 1.250,  2.500) = 16460 
    [ 2.500,  3.750) = 461 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.642 ms/op
     p(50.0000) =      1.751 ms/op
     p(90.0000) =      2.216 ms/op
     p(95.0000) =      2.351 ms/op
     p(99.0000) =      2.860 ms/op
     p(99.9000) =     18.153 ms/op
     p(99.9900) =     18.832 ms/op
     p(99.9990) =     18.907 ms/op
     p(99.9999) =     18.907 ms/op
    p(100.0000) =     18.907 ms/op


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
# Warmup Iteration   1: 4.336 ±(99.9%) 0.099 ms/op
Iteration   1: 3.137 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   1.120 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.940 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  7.573 ms/op
                 getUser·p0.9999: 8.363 ms/op
                 getUser·p1.00:   8.364 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10198
  mean =      3.137 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 17 
    [1.500, 2.000) = 108 
    [2.000, 2.500) = 1704 
    [2.500, 3.000) = 2944 
    [3.000, 3.500) = 2726 
    [3.500, 4.000) = 1846 
    [4.000, 4.500) = 464 
    [4.500, 5.000) = 218 
    [5.000, 5.500) = 47 
    [5.500, 6.000) = 31 
    [6.000, 6.500) = 19 
    [6.500, 7.000) = 40 
    [7.000, 7.500) = 22 
    [7.500, 8.000) = 10 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.120 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      5.882 ms/op
     p(99.9000) =      7.573 ms/op
     p(99.9900) =      8.363 ms/op
     p(99.9990) =      8.364 ms/op
     p(99.9999) =      8.364 ms/op
    p(100.0000) =      8.364 ms/op


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
# Warmup Iteration   1: 13.145 ±(99.9%) 0.474 ms/op
Iteration   1: 8.351 ±(99.9%) 0.101 ms/op
                 listUser·p0.00:   3.478 ms/op
                 listUser·p0.50:   8.110 ms/op
                 listUser·p0.90:   10.682 ms/op
                 listUser·p0.95:   11.928 ms/op
                 listUser·p0.99:   14.048 ms/op
                 listUser·p0.999:  17.340 ms/op
                 listUser·p0.9999: 18.547 ms/op
                 listUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3839
  mean =      8.351 ±(99.9%) 0.101 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 0 
    [ 2.500,  3.750) = 5 
    [ 3.750,  5.000) = 58 
    [ 5.000,  6.250) = 355 
    [ 6.250,  7.500) = 919 
    [ 7.500,  8.750) = 1108 
    [ 8.750, 10.000) = 746 
    [10.000, 11.250) = 386 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 104 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      3.478 ms/op
     p(50.0000) =      8.110 ms/op
     p(90.0000) =     10.682 ms/op
     p(95.0000) =     11.928 ms/op
     p(99.0000) =     14.048 ms/op
     p(99.9000) =     17.340 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.392          ops/ms
Client.existUser                       thrpt         14.157          ops/ms
Client.getUser                         thrpt          8.403          ops/ms
Client.listUser                        thrpt          3.649          ops/ms
Client.createUser                       avgt          2.959           ms/op
Client.existUser                        avgt          2.031           ms/op
Client.getUser                          avgt          3.029           ms/op
Client.listUser                         avgt          8.509           ms/op
Client.createUser                     sample  11355   2.813 ± 0.029   ms/op
Client.createUser:createUser·p0.00    sample          0.986           ms/op
Client.createUser:createUser·p0.50    sample          2.748           ms/op
Client.createUser:createUser·p0.90    sample          3.305           ms/op
Client.createUser:createUser·p0.95    sample          3.592           ms/op
Client.createUser:createUser·p0.99    sample          5.354           ms/op
Client.createUser:createUser·p0.999   sample         17.236           ms/op
Client.createUser:createUser·p0.9999  sample         17.618           ms/op
Client.createUser:createUser·p1.00    sample         17.662           ms/op
Client.existUser                      sample  17684   1.829 ± 0.019   ms/op
Client.existUser:existUser·p0.00      sample          0.642           ms/op
Client.existUser:existUser·p0.50      sample          1.751           ms/op
Client.existUser:existUser·p0.90      sample          2.216           ms/op
Client.existUser:existUser·p0.95      sample          2.351           ms/op
Client.existUser:existUser·p0.99      sample          2.860           ms/op
Client.existUser:existUser·p0.999     sample         18.153           ms/op
Client.existUser:existUser·p0.9999    sample         18.832           ms/op
Client.existUser:existUser·p1.00      sample         18.907           ms/op
Client.getUser                        sample  10198   3.137 ± 0.024   ms/op
Client.getUser:getUser·p0.00          sample          1.120           ms/op
Client.getUser:getUser·p0.50          sample          3.068           ms/op
Client.getUser:getUser·p0.90          sample          3.940           ms/op
Client.getUser:getUser·p0.95          sample          4.276           ms/op
Client.getUser:getUser·p0.99          sample          5.882           ms/op
Client.getUser:getUser·p0.999         sample          7.573           ms/op
Client.getUser:getUser·p0.9999        sample          8.363           ms/op
Client.getUser:getUser·p1.00          sample          8.364           ms/op
Client.listUser                       sample   3839   8.351 ± 0.101   ms/op
Client.listUser:listUser·p0.00        sample          3.478           ms/op
Client.listUser:listUser·p0.50        sample          8.110           ms/op
Client.listUser:listUser·p0.90        sample         10.682           ms/op
Client.listUser:listUser·p0.95        sample         11.928           ms/op
Client.listUser:listUser·p0.99        sample         14.048           ms/op
Client.listUser:listUser·p0.999       sample         17.340           ms/op
Client.listUser:listUser·p0.9999      sample         18.547           ms/op
Client.listUser:listUser·p1.00        sample         18.547           ms/op
