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
# Warmup Iteration   1: 1.706 ops/ms
Iteration   1: 7.040 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.040 ops/ms


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
# Warmup Iteration   1: 5.910 ops/ms
Iteration   1: 13.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.133 ops/ms


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
# Warmup Iteration   1: 6.788 ops/ms
Iteration   1: 14.814 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.814 ops/ms


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
# Warmup Iteration   1: 5.028 ops/ms
Iteration   1: 8.079 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.079 ops/ms


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
# Warmup Iteration   1: 4.007 ±(99.9%) 0.076 ms/op
Iteration   1: 2.277 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.277 ms/op


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
# Warmup Iteration   1: 3.263 ±(99.9%) 0.053 ms/op
Iteration   1: 1.688 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.688 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.378 ±(99.9%) 0.059 ms/op
Iteration   1: 2.213 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.213 ms/op


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
# Warmup Iteration   1: 4.347 ±(99.9%) 0.091 ms/op
Iteration   1: 3.502 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.502 ms/op


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
# Warmup Iteration   1: 3.534 ±(99.9%) 0.084 ms/op
Iteration   1: 2.282 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.633 ms/op
                 createUser·p0.50:   2.126 ms/op
                 createUser·p0.90:   2.765 ms/op
                 createUser·p0.95:   3.080 ms/op
                 createUser·p0.99:   5.824 ms/op
                 createUser·p0.999:  14.303 ms/op
                 createUser·p0.9999: 15.126 ms/op
                 createUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14003
  mean =      2.282 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 86 
    [ 1.250,  2.500) = 11140 
    [ 2.500,  3.750) = 2489 
    [ 3.750,  5.000) = 88 
    [ 5.000,  6.250) = 68 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 63 
    [13.750, 15.000) = 29 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.633 ms/op
     p(50.0000) =      2.126 ms/op
     p(90.0000) =      2.765 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      5.824 ms/op
     p(99.9000) =     14.303 ms/op
     p(99.9900) =     15.126 ms/op
     p(99.9990) =     15.139 ms/op
     p(99.9999) =     15.139 ms/op
    p(100.0000) =     15.139 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.122 ±(99.9%) 0.085 ms/op
Iteration   1: 1.976 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   1.892 ms/op
                 existUser·p0.90:   2.396 ms/op
                 existUser·p0.95:   2.597 ms/op
                 existUser·p0.99:   3.970 ms/op
                 existUser·p0.999:  22.112 ms/op
                 existUser·p0.9999: 23.925 ms/op
                 existUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16195
  mean =      1.976 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15097 
    [ 2.500,  5.000) = 962 
    [ 5.000,  7.500) = 72 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.892 ms/op
     p(90.0000) =      2.396 ms/op
     p(95.0000) =      2.597 ms/op
     p(99.0000) =      3.970 ms/op
     p(99.9000) =     22.112 ms/op
     p(99.9900) =     23.925 ms/op
     p(99.9990) =     23.986 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


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
# Warmup Iteration   1: 3.458 ±(99.9%) 0.093 ms/op
Iteration   1: 2.137 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.748 ms/op
                 getUser·p0.50:   2.058 ms/op
                 getUser·p0.90:   2.716 ms/op
                 getUser·p0.95:   2.978 ms/op
                 getUser·p0.99:   4.825 ms/op
                 getUser·p0.999:  10.473 ms/op
                 getUser·p0.9999: 10.980 ms/op
                 getUser·p1.00:   11.256 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15096
  mean =      2.137 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 217 
    [ 1.250,  2.500) = 12000 
    [ 2.500,  3.750) = 2640 
    [ 3.750,  5.000) = 109 
    [ 5.000,  6.250) = 98 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 10 
    [10.000, 11.250) = 21 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.058 ms/op
     p(90.0000) =      2.716 ms/op
     p(95.0000) =      2.978 ms/op
     p(99.0000) =      4.825 ms/op
     p(99.9000) =     10.473 ms/op
     p(99.9900) =     10.980 ms/op
     p(99.9990) =     11.256 ms/op
     p(99.9999) =     11.256 ms/op
    p(100.0000) =     11.256 ms/op


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
# Warmup Iteration   1: 4.311 ±(99.9%) 0.147 ms/op
Iteration   1: 3.497 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.356 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.300 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.724 ms/op
                 listUser·p0.999:  9.137 ms/op
                 listUser·p0.9999: 9.617 ms/op
                 listUser·p1.00:   9.617 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9220
  mean =      3.497 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 9 
    [ 1.500,  2.000) = 33 
    [ 2.000,  2.500) = 596 
    [ 2.500,  3.000) = 1900 
    [ 3.000,  3.500) = 2028 
    [ 3.500,  4.000) = 2938 
    [ 4.000,  4.500) = 1166 
    [ 4.500,  5.000) = 277 
    [ 5.000,  5.500) = 71 
    [ 5.500,  6.000) = 37 
    [ 6.000,  6.500) = 67 
    [ 6.500,  7.000) = 53 
    [ 7.000,  7.500) = 35 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 0 
    [ 8.500,  9.000) = 0 
    [ 9.000,  9.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.356 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.300 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.724 ms/op
     p(99.9000) =      9.137 ms/op
     p(99.9900) =      9.617 ms/op
     p(99.9990) =      9.617 ms/op
     p(99.9999) =      9.617 ms/op
    p(100.0000) =      9.617 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.040          ops/ms
ClientSimple.existUser                       thrpt         13.133          ops/ms
ClientSimple.getUser                         thrpt         14.814          ops/ms
ClientSimple.listUser                        thrpt          8.079          ops/ms
ClientSimple.createUser                       avgt          2.277           ms/op
ClientSimple.existUser                        avgt          1.688           ms/op
ClientSimple.getUser                          avgt          2.213           ms/op
ClientSimple.listUser                         avgt          3.502           ms/op
ClientSimple.createUser                     sample  14003   2.282 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.633           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.126           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.080           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.824           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.303           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.126           ms/op
ClientSimple.createUser:createUser·p1.00    sample         15.139           ms/op
ClientSimple.existUser                      sample  16195   1.976 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.428           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.892           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.396           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.597           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.970           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.112           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.925           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.986           ms/op
ClientSimple.getUser                        sample  15096   2.137 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.748           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.058           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.716           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.978           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.825           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.473           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.980           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.256           ms/op
ClientSimple.listUser                       sample   9220   3.497 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.356           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.300           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.724           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.137           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.617           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.617           ms/op

Benchmark result is saved to 1723768983462.json
