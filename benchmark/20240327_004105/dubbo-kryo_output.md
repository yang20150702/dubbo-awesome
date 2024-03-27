# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.088 ops/ms
Iteration   1: 7.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.212 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.429 ops/ms
Iteration   1: 13.016 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.016 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.015 ops/ms
Iteration   1: 14.386 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.386 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.536 ops/ms
Iteration   1: 7.705 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.705 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.253 ±(99.9%) 0.079 ms/op
Iteration   1: 2.084 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.084 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.302 ±(99.9%) 0.054 ms/op
Iteration   1: 1.983 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.340 ±(99.9%) 0.059 ms/op
Iteration   1: 1.993 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.993 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.439 ±(99.9%) 0.109 ms/op
Iteration   1: 3.711 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.224 ±(99.9%) 0.087 ms/op
Iteration   1: 2.080 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.754 ms/op
                 createUser·p0.50:   1.798 ms/op
                 createUser·p0.90:   2.507 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   9.110 ms/op
                 createUser·p0.999:  18.862 ms/op
                 createUser·p0.9999: 20.349 ms/op
                 createUser·p1.00:   20.349 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15376
  mean =      2.080 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13820 
    [ 2.500,  5.000) = 1292 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 40 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.754 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.507 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      9.110 ms/op
     p(99.9000) =     18.862 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     20.349 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.042 ±(99.9%) 0.075 ms/op
Iteration   1: 2.219 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.605 ms/op
                 existUser·p0.50:   2.200 ms/op
                 existUser·p0.90:   2.613 ms/op
                 existUser·p0.95:   2.799 ms/op
                 existUser·p0.99:   3.706 ms/op
                 existUser·p0.999:  13.232 ms/op
                 existUser·p0.9999: 13.689 ms/op
                 existUser·p1.00:   13.812 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14410
  mean =      2.219 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 138 
    [ 1.250,  2.500) = 12028 
    [ 2.500,  3.750) = 2105 
    [ 3.750,  5.000) = 73 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 50 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.200 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      2.799 ms/op
     p(99.0000) =      3.706 ms/op
     p(99.9000) =     13.232 ms/op
     p(99.9900) =     13.689 ms/op
     p(99.9990) =     13.812 ms/op
     p(99.9999) =     13.812 ms/op
    p(100.0000) =     13.812 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.314 ±(99.9%) 0.078 ms/op
Iteration   1: 2.331 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.677 ms/op
                 getUser·p0.50:   2.175 ms/op
                 getUser·p0.90:   2.916 ms/op
                 getUser·p0.95:   3.183 ms/op
                 getUser·p0.99:   5.595 ms/op
                 getUser·p0.999:  18.874 ms/op
                 getUser·p0.9999: 19.316 ms/op
                 getUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13763
  mean =      2.331 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 166 
    [ 1.250,  2.500) = 9740 
    [ 2.500,  3.750) = 3547 
    [ 3.750,  5.000) = 115 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 30 
    [17.500, 18.750) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.175 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.183 ms/op
     p(99.0000) =      5.595 ms/op
     p(99.9000) =     18.874 ms/op
     p(99.9900) =     19.316 ms/op
     p(99.9990) =     19.464 ms/op
     p(99.9999) =     19.464 ms/op
    p(100.0000) =     19.464 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.587 ±(99.9%) 0.140 ms/op
Iteration   1: 3.130 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.178 ms/op
                 listUser·p0.50:   2.937 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.162 ms/op
                 listUser·p0.99:   4.825 ms/op
                 listUser·p0.999:  6.599 ms/op
                 listUser·p0.9999: 8.298 ms/op
                 listUser·p1.00:   8.331 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10215
  mean =      3.130 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 3 
    [1.500, 2.000) = 58 
    [2.000, 2.500) = 940 
    [2.500, 3.000) = 4471 
    [3.000, 3.500) = 1933 
    [3.500, 4.000) = 1912 
    [4.000, 4.500) = 712 
    [4.500, 5.000) = 91 
    [5.000, 5.500) = 30 
    [5.500, 6.000) = 25 
    [6.000, 6.500) = 28 
    [6.500, 7.000) = 11 
    [7.000, 7.500) = 0 
    [7.500, 8.000) = 0 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.178 ms/op
     p(50.0000) =      2.937 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.162 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =      6.599 ms/op
     p(99.9900) =      8.298 ms/op
     p(99.9990) =      8.331 ms/op
     p(99.9999) =      8.331 ms/op
    p(100.0000) =      8.331 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.212          ops/ms
ClientSimple.existUser                       thrpt         13.016          ops/ms
ClientSimple.getUser                         thrpt         14.386          ops/ms
ClientSimple.listUser                        thrpt          7.705          ops/ms
ClientSimple.createUser                       avgt          2.084           ms/op
ClientSimple.existUser                        avgt          1.983           ms/op
ClientSimple.getUser                          avgt          1.993           ms/op
ClientSimple.listUser                         avgt          3.711           ms/op
ClientSimple.createUser                     sample  15376   2.080 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.754           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.798           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.507           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.110           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.862           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.349           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.349           ms/op
ClientSimple.existUser                      sample  14410   2.219 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.605           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.200           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.613           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.799           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.706           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.232           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.689           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.812           ms/op
ClientSimple.getUser                        sample  13763   2.331 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.677           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.175           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.183           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.595           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.874           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.316           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.464           ms/op
ClientSimple.listUser                       sample  10215   3.130 ± 0.020   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.178           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.937           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.961           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.162           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.825           ms/op
ClientSimple.listUser:listUser·p0.999       sample          6.599           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.298           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.331           ms/op

Benchmark result is saved to 1711499813441.json
