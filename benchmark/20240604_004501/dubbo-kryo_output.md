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
# Warmup Iteration   1: 1.762 ops/ms
Iteration   1: 7.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.428 ops/ms


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
# Warmup Iteration   1: 6.475 ops/ms
Iteration   1: 12.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.961 ops/ms


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
# Warmup Iteration   1: 5.840 ops/ms
Iteration   1: 12.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.874 ops/ms


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
# Warmup Iteration   1: 5.336 ops/ms
Iteration   1: 8.597 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.597 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.809 ±(99.9%) 0.066 ms/op
Iteration   1: 2.153 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.153 ms/op


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
# Warmup Iteration   1: 3.133 ±(99.9%) 0.046 ms/op
Iteration   1: 1.905 ±(99.9%) 0.005 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.493 ±(99.9%) 0.058 ms/op
Iteration   1: 2.087 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.087 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.523 ±(99.9%) 0.074 ms/op
Iteration   1: 3.612 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.612 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.678 ±(99.9%) 0.097 ms/op
Iteration   1: 2.485 ±(99.9%) 0.045 ms/op
                 createUser·p0.00:   0.548 ms/op
                 createUser·p0.50:   2.433 ms/op
                 createUser·p0.90:   3.027 ms/op
                 createUser·p0.95:   3.334 ms/op
                 createUser·p0.99:   5.120 ms/op
                 createUser·p0.999:  27.086 ms/op
                 createUser·p0.9999: 27.278 ms/op
                 createUser·p1.00:   27.329 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13077
  mean =      2.485 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7195 
    [ 2.500,  5.000) = 5726 
    [ 5.000,  7.500) = 63 
    [ 7.500, 10.000) = 29 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.548 ms/op
     p(50.0000) =      2.433 ms/op
     p(90.0000) =      3.027 ms/op
     p(95.0000) =      3.334 ms/op
     p(99.0000) =      5.120 ms/op
     p(99.9000) =     27.086 ms/op
     p(99.9900) =     27.278 ms/op
     p(99.9990) =     27.329 ms/op
     p(99.9999) =     27.329 ms/op
    p(100.0000) =     27.329 ms/op


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
# Warmup Iteration   1: 3.020 ±(99.9%) 0.064 ms/op
Iteration   1: 1.986 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.531 ms/op
                 existUser·p0.50:   1.862 ms/op
                 existUser·p0.90:   2.421 ms/op
                 existUser·p0.95:   2.585 ms/op
                 existUser·p0.99:   6.078 ms/op
                 existUser·p0.999:  20.218 ms/op
                 existUser·p0.9999: 20.990 ms/op
                 existUser·p1.00:   21.070 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16104
  mean =      1.986 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14928 
    [ 2.500,  5.000) = 988 
    [ 5.000,  7.500) = 124 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.531 ms/op
     p(50.0000) =      1.862 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.585 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     20.218 ms/op
     p(99.9900) =     20.990 ms/op
     p(99.9990) =     21.070 ms/op
     p(99.9999) =     21.070 ms/op
    p(100.0000) =     21.070 ms/op


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
# Warmup Iteration   1: 3.417 ±(99.9%) 0.104 ms/op
Iteration   1: 2.098 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   0.346 ms/op
                 getUser·p0.50:   1.944 ms/op
                 getUser·p0.90:   2.535 ms/op
                 getUser·p0.95:   2.769 ms/op
                 getUser·p0.99:   4.406 ms/op
                 getUser·p0.999:  15.761 ms/op
                 getUser·p0.9999: 16.021 ms/op
                 getUser·p1.00:   16.073 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15239
  mean =      2.098 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 139 
    [ 1.250,  2.500) = 13424 
    [ 2.500,  3.750) = 1424 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 30 
    [12.500, 13.750) = 2 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.346 ms/op
     p(50.0000) =      1.944 ms/op
     p(90.0000) =      2.535 ms/op
     p(95.0000) =      2.769 ms/op
     p(99.0000) =      4.406 ms/op
     p(99.9000) =     15.761 ms/op
     p(99.9900) =     16.021 ms/op
     p(99.9990) =     16.073 ms/op
     p(99.9999) =     16.073 ms/op
    p(100.0000) =     16.073 ms/op


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
# Warmup Iteration   1: 4.722 ±(99.9%) 0.155 ms/op
Iteration   1: 3.371 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   1.147 ms/op
                 listUser·p0.50:   3.461 ms/op
                 listUser·p0.90:   4.063 ms/op
                 listUser·p0.95:   4.606 ms/op
                 listUser·p0.99:   5.800 ms/op
                 listUser·p0.999:  7.487 ms/op
                 listUser·p0.9999: 8.618 ms/op
                 listUser·p1.00:   8.618 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9493
  mean =      3.371 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 43 
    [1.500, 2.000) = 250 
    [2.000, 2.500) = 1067 
    [2.500, 3.000) = 1267 
    [3.000, 3.500) = 2430 
    [3.500, 4.000) = 3306 
    [4.000, 4.500) = 619 
    [4.500, 5.000) = 220 
    [5.000, 5.500) = 143 
    [5.500, 6.000) = 70 
    [6.000, 6.500) = 36 
    [6.500, 7.000) = 7 
    [7.000, 7.500) = 28 
    [7.500, 8.000) = 4 
    [8.000, 8.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.147 ms/op
     p(50.0000) =      3.461 ms/op
     p(90.0000) =      4.063 ms/op
     p(95.0000) =      4.606 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =      7.487 ms/op
     p(99.9900) =      8.618 ms/op
     p(99.9990) =      8.618 ms/op
     p(99.9999) =      8.618 ms/op
    p(100.0000) =      8.618 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.428          ops/ms
ClientSimple.existUser                       thrpt         12.961          ops/ms
ClientSimple.getUser                         thrpt         12.874          ops/ms
ClientSimple.listUser                        thrpt          8.597          ops/ms
ClientSimple.createUser                       avgt          2.153           ms/op
ClientSimple.existUser                        avgt          1.905           ms/op
ClientSimple.getUser                          avgt          2.087           ms/op
ClientSimple.listUser                         avgt          3.612           ms/op
ClientSimple.createUser                     sample  13077   2.485 ± 0.045   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.548           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.433           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.027           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.334           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.120           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.086           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.278           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.329           ms/op
ClientSimple.existUser                      sample  16104   1.986 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.531           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.862           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.421           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.585           ms/op
ClientSimple.existUser:existUser·p0.99      sample          6.078           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.218           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.990           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.070           ms/op
ClientSimple.getUser                        sample  15239   2.098 ± 0.024   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.346           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.944           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.535           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.769           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.406           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.761           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.021           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.073           ms/op
ClientSimple.listUser                       sample   9493   3.371 ± 0.026   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.147           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.461           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.063           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.606           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.800           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.487           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.618           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.618           ms/op

Benchmark result is saved to 1717461617854.json
