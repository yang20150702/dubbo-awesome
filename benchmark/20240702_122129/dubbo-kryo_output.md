# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.994 ops/ms
Iteration   1: 7.075 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.075 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.014 ops/ms
Iteration   1: 12.182 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.182 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.183 ops/ms
Iteration   1: 13.099 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.099 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.179 ops/ms
Iteration   1: 8.044 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.044 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.776 ±(99.9%) 0.105 ms/op
Iteration   1: 2.517 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.517 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.442 ±(99.9%) 0.062 ms/op
Iteration   1: 1.905 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.905 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.065 ±(99.9%) 0.063 ms/op
Iteration   1: 2.059 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.059 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.665 ±(99.9%) 0.090 ms/op
Iteration   1: 4.430 ±(99.9%) 0.058 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.430 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.320 ±(99.9%) 0.080 ms/op
Iteration   1: 2.448 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.490 ms/op
                 createUser·p0.50:   2.269 ms/op
                 createUser·p0.90:   2.879 ms/op
                 createUser·p0.95:   3.519 ms/op
                 createUser·p0.99:   7.905 ms/op
                 createUser·p0.999:  15.434 ms/op
                 createUser·p0.9999: 17.900 ms/op
                 createUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13457
  mean =      2.448 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 252 
    [ 1.250,  2.500) = 9702 
    [ 2.500,  3.750) = 2944 
    [ 3.750,  5.000) = 199 
    [ 5.000,  6.250) = 117 
    [ 6.250,  7.500) = 50 
    [ 7.500,  8.750) = 74 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 5 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 37 
    [13.750, 15.000) = 33 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.490 ms/op
     p(50.0000) =      2.269 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.519 ms/op
     p(99.0000) =      7.905 ms/op
     p(99.9000) =     15.434 ms/op
     p(99.9900) =     17.900 ms/op
     p(99.9990) =     17.957 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.364 ±(99.9%) 0.081 ms/op
Iteration   1: 1.989 ±(99.9%) 0.053 ms/op
                 existUser·p0.00:   0.495 ms/op
                 existUser·p0.50:   1.722 ms/op
                 existUser·p0.90:   2.339 ms/op
                 existUser·p0.95:   2.523 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  29.418 ms/op
                 existUser·p0.9999: 58.746 ms/op
                 existUser·p1.00:   58.786 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16073
  mean =      1.989 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15885 
    [ 5.000, 10.000) = 98 
    [10.000, 15.000) = 34 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 46 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 2 
    [50.000, 55.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.495 ms/op
     p(50.0000) =      1.722 ms/op
     p(90.0000) =      2.339 ms/op
     p(95.0000) =      2.523 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     29.418 ms/op
     p(99.9900) =     58.746 ms/op
     p(99.9990) =     58.786 ms/op
     p(99.9999) =     58.786 ms/op
    p(100.0000) =     58.786 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.335 ±(99.9%) 0.078 ms/op
Iteration   1: 2.420 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.545 ms/op
                 getUser·p0.50:   2.421 ms/op
                 getUser·p0.90:   2.855 ms/op
                 getUser·p0.95:   3.084 ms/op
                 getUser·p0.99:   3.830 ms/op
                 getUser·p0.999:  13.493 ms/op
                 getUser·p0.9999: 14.413 ms/op
                 getUser·p1.00:   14.418 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13289
  mean =      2.420 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 75 
    [ 1.250,  2.500) = 7727 
    [ 2.500,  3.750) = 5298 
    [ 3.750,  5.000) = 116 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 3 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 5 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.545 ms/op
     p(50.0000) =      2.421 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.084 ms/op
     p(99.0000) =      3.830 ms/op
     p(99.9000) =     13.493 ms/op
     p(99.9900) =     14.413 ms/op
     p(99.9990) =     14.418 ms/op
     p(99.9999) =     14.418 ms/op
    p(100.0000) =     14.418 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.900 ±(99.9%) 0.136 ms/op
Iteration   1: 3.352 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.296 ms/op
                 listUser·p0.50:   2.970 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   6.064 ms/op
                 listUser·p0.999:  30.310 ms/op
                 listUser·p0.9999: 30.474 ms/op
                 listUser·p1.00:   30.474 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9507
  mean =      3.352 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 364 
    [ 2.500,  5.000) = 8870 
    [ 5.000,  7.500) = 230 
    [ 7.500, 10.000) = 11 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.296 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      6.064 ms/op
     p(99.9000) =     30.310 ms/op
     p(99.9900) =     30.474 ms/op
     p(99.9990) =     30.474 ms/op
     p(99.9999) =     30.474 ms/op
    p(100.0000) =     30.474 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.075          ops/ms
ClientSimple.existUser                       thrpt         12.182          ops/ms
ClientSimple.getUser                         thrpt         13.099          ops/ms
ClientSimple.listUser                        thrpt          8.044          ops/ms
ClientSimple.createUser                       avgt          2.517           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          2.059           ms/op
ClientSimple.listUser                         avgt          4.430           ms/op
ClientSimple.createUser                     sample  13457   2.448 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.490           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.269           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.519           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.905           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.434           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.900           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.957           ms/op
ClientSimple.existUser                      sample  16073   1.989 ± 0.053   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.495           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.722           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.339           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.523           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.521           ms/op
ClientSimple.existUser:existUser·p0.999     sample         29.418           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         58.746           ms/op
ClientSimple.existUser:existUser·p1.00      sample         58.786           ms/op
ClientSimple.getUser                        sample  13289   2.420 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.545           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.855           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.084           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.830           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.493           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         14.413           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.418           ms/op
ClientSimple.listUser                       sample   9507   3.352 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.296           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.970           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.276           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.604           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.064           ms/op
ClientSimple.listUser:listUser·p0.999       sample         30.310           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.474           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.474           ms/op

Benchmark result is saved to 1719922615201.json
