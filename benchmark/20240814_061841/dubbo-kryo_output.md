# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.037 ops/ms
Iteration   1: 7.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.762 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.295 ops/ms
Iteration   1: 13.073 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.073 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.292 ops/ms
Iteration   1: 13.371 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.371 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 5.848 ops/ms
Iteration   1: 8.644 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.644 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.478 ±(99.9%) 0.133 ms/op
Iteration   1: 1.947 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.947 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.356 ±(99.9%) 0.053 ms/op
Iteration   1: 2.249 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.249 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.269 ±(99.9%) 0.054 ms/op
Iteration   1: 1.814 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.814 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.811 ±(99.9%) 0.093 ms/op
Iteration   1: 3.408 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.408 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.499 ±(99.9%) 0.079 ms/op
Iteration   1: 2.018 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   1.839 ms/op
                 createUser·p0.90:   2.277 ms/op
                 createUser·p0.95:   2.515 ms/op
                 createUser·p0.99:   6.755 ms/op
                 createUser·p0.999:  26.771 ms/op
                 createUser·p0.9999: 30.212 ms/op
                 createUser·p1.00:   30.212 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15839
  mean =      2.018 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15017 
    [ 2.500,  5.000) = 652 
    [ 5.000,  7.500) = 71 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 29 
    [12.500, 15.000) = 35 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 1 
    [30.000, 32.500) = 4 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      1.839 ms/op
     p(90.0000) =      2.277 ms/op
     p(95.0000) =      2.515 ms/op
     p(99.0000) =      6.755 ms/op
     p(99.9000) =     26.771 ms/op
     p(99.9900) =     30.212 ms/op
     p(99.9990) =     30.212 ms/op
     p(99.9999) =     30.212 ms/op
    p(100.0000) =     30.212 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.943 ±(99.9%) 0.061 ms/op
Iteration   1: 1.945 ±(99.9%) 0.033 ms/op
                 existUser·p0.00:   0.577 ms/op
                 existUser·p0.50:   1.802 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.593 ms/op
                 existUser·p0.99:   5.215 ms/op
                 existUser·p0.999:  20.578 ms/op
                 existUser·p0.9999: 20.611 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16540
  mean =      1.945 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15475 
    [ 2.500,  5.000) = 885 
    [ 5.000,  7.500) = 116 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.577 ms/op
     p(50.0000) =      1.802 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      5.215 ms/op
     p(99.9000) =     20.578 ms/op
     p(99.9900) =     20.611 ms/op
     p(99.9990) =     20.611 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 2.963 ±(99.9%) 0.074 ms/op
Iteration   1: 1.977 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.009 ms/op
                 getUser·p0.50:   1.825 ms/op
                 getUser·p0.90:   2.597 ms/op
                 getUser·p0.95:   2.874 ms/op
                 getUser·p0.99:   3.417 ms/op
                 getUser·p0.999:  5.066 ms/op
                 getUser·p0.9999: 6.234 ms/op
                 getUser·p1.00:   6.734 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16287
  mean =      1.977 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 732 
    [1.500, 2.000) = 9903 
    [2.000, 2.500) = 3497 
    [2.500, 3.000) = 1595 
    [3.000, 3.500) = 443 
    [3.500, 4.000) = 65 
    [4.000, 4.500) = 17 
    [4.500, 5.000) = 14 
    [5.000, 5.500) = 15 
    [5.500, 6.000) = 5 
    [6.000, 6.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.009 ms/op
     p(50.0000) =      1.825 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.874 ms/op
     p(99.0000) =      3.417 ms/op
     p(99.9000) =      5.066 ms/op
     p(99.9900) =      6.234 ms/op
     p(99.9990) =      6.734 ms/op
     p(99.9999) =      6.734 ms/op
    p(100.0000) =      6.734 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_422, OpenJDK 64-Bit Server VM, 25.422-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.422-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 5.346 ±(99.9%) 0.172 ms/op
Iteration   1: 3.540 ±(99.9%) 0.038 ms/op
                 listUser·p0.00:   0.932 ms/op
                 listUser·p0.50:   3.502 ms/op
                 listUser·p0.90:   4.530 ms/op
                 listUser·p0.95:   4.957 ms/op
                 listUser·p0.99:   7.706 ms/op
                 listUser·p0.999:  11.972 ms/op
                 listUser·p0.9999: 13.713 ms/op
                 listUser·p1.00:   13.713 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9037
  mean =      3.540 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 18 
    [ 1.250,  2.500) = 1119 
    [ 2.500,  3.750) = 4489 
    [ 3.750,  5.000) = 2980 
    [ 5.000,  6.250) = 301 
    [ 6.250,  7.500) = 35 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 11 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.932 ms/op
     p(50.0000) =      3.502 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.957 ms/op
     p(99.0000) =      7.706 ms/op
     p(99.9000) =     11.972 ms/op
     p(99.9900) =     13.713 ms/op
     p(99.9990) =     13.713 ms/op
     p(99.9999) =     13.713 ms/op
    p(100.0000) =     13.713 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.762          ops/ms
ClientSimple.existUser                       thrpt         13.073          ops/ms
ClientSimple.getUser                         thrpt         13.371          ops/ms
ClientSimple.listUser                        thrpt          8.644          ops/ms
ClientSimple.createUser                       avgt          1.947           ms/op
ClientSimple.existUser                        avgt          2.249           ms/op
ClientSimple.getUser                          avgt          1.814           ms/op
ClientSimple.listUser                         avgt          3.408           ms/op
ClientSimple.createUser                     sample  15839   2.018 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.549           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.839           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.277           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.515           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.755           ms/op
ClientSimple.createUser:createUser·p0.999   sample         26.771           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.212           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.212           ms/op
ClientSimple.existUser                      sample  16540   1.945 ± 0.033   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.577           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.802           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.593           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.215           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.578           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.611           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.611           ms/op
ClientSimple.getUser                        sample  16287   1.977 ± 0.012   ms/op
ClientSimple.getUser:getUser·p0.00          sample          1.009           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.825           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.597           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.874           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.417           ms/op
ClientSimple.getUser:getUser·p0.999         sample          5.066           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          6.234           ms/op
ClientSimple.getUser:getUser·p1.00          sample          6.734           ms/op
ClientSimple.listUser                       sample   9037   3.540 ± 0.038   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.932           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.502           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.957           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.706           ms/op
ClientSimple.listUser:listUser·p0.999       sample         11.972           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         13.713           ms/op
ClientSimple.listUser:listUser·p1.00        sample         13.713           ms/op

Benchmark result is saved to 1723616027342.json
