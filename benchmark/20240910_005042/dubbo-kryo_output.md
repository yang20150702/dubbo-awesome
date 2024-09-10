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
# Warmup Iteration   1: 1.242 ops/ms
Iteration   1: 5.307 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.307 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 4.754 ops/ms
Iteration   1: 10.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.289 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.802 ops/ms
Iteration   1: 11.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.029 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.738 ops/ms
Iteration   1: 7.394 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.394 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.163 ±(99.9%) 0.083 ms/op
Iteration   1: 2.337 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.337 ms/op


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
# Warmup Iteration   1: 3.539 ±(99.9%) 0.069 ms/op
Iteration   1: 1.987 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.987 ms/op


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
# Warmup Iteration   1: 3.409 ±(99.9%) 0.074 ms/op
Iteration   1: 2.073 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.073 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.610 ±(99.9%) 0.086 ms/op
Iteration   1: 4.199 ±(99.9%) 0.028 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  4.199 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.690 ±(99.9%) 0.108 ms/op
Iteration   1: 2.571 ±(99.9%) 0.053 ms/op
                 createUser·p0.00:   0.549 ms/op
                 createUser·p0.50:   2.281 ms/op
                 createUser·p0.90:   3.056 ms/op
                 createUser·p0.95:   4.108 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  27.054 ms/op
                 createUser·p0.9999: 28.017 ms/op
                 createUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12463
  mean =      2.571 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8734 
    [ 2.500,  5.000) = 3331 
    [ 5.000,  7.500) = 200 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 81 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.549 ms/op
     p(50.0000) =      2.281 ms/op
     p(90.0000) =      3.056 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =     10.748 ms/op
     p(99.9000) =     27.054 ms/op
     p(99.9900) =     28.017 ms/op
     p(99.9990) =     28.049 ms/op
     p(99.9999) =     28.049 ms/op
    p(100.0000) =     28.049 ms/op


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
# Warmup Iteration   1: 3.263 ±(99.9%) 0.081 ms/op
Iteration   1: 2.114 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.606 ms/op
                 existUser·p0.50:   2.042 ms/op
                 existUser·p0.90:   2.785 ms/op
                 existUser·p0.95:   3.027 ms/op
                 existUser·p0.99:   4.711 ms/op
                 existUser·p0.999:  14.269 ms/op
                 existUser·p0.9999: 14.872 ms/op
                 existUser·p1.00:   15.139 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15097
  mean =      2.114 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 836 
    [ 1.250,  2.500) = 10880 
    [ 2.500,  3.750) = 3091 
    [ 3.750,  5.000) = 168 
    [ 5.000,  6.250) = 21 
    [ 6.250,  7.500) = 26 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 33 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 9 
    [13.750, 15.000) = 22 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.606 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.785 ms/op
     p(95.0000) =      3.027 ms/op
     p(99.0000) =      4.711 ms/op
     p(99.9000) =     14.269 ms/op
     p(99.9900) =     14.872 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.458 ±(99.9%) 0.091 ms/op
Iteration   1: 2.109 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.511 ms/op
                 getUser·p0.50:   1.929 ms/op
                 getUser·p0.90:   2.795 ms/op
                 getUser·p0.95:   3.097 ms/op
                 getUser·p0.99:   4.014 ms/op
                 getUser·p0.999:  18.448 ms/op
                 getUser·p0.9999: 19.233 ms/op
                 getUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15145
  mean =      2.109 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 516 
    [ 1.250,  2.500) = 11559 
    [ 2.500,  3.750) = 2821 
    [ 3.750,  5.000) = 168 
    [ 5.000,  6.250) = 14 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 24 

  Percentiles, ms/op:
      p(0.0000) =      0.511 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.795 ms/op
     p(95.0000) =      3.097 ms/op
     p(99.0000) =      4.014 ms/op
     p(99.9000) =     18.448 ms/op
     p(99.9900) =     19.233 ms/op
     p(99.9990) =     19.300 ms/op
     p(99.9999) =     19.300 ms/op
    p(100.0000) =     19.300 ms/op


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
# Warmup Iteration   1: 5.174 ±(99.9%) 0.163 ms/op
Iteration   1: 3.752 ±(99.9%) 0.099 ms/op
                 listUser·p0.00:   1.104 ms/op
                 listUser·p0.50:   3.482 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   5.161 ms/op
                 listUser·p0.99:   8.967 ms/op
                 listUser·p0.999:  45.941 ms/op
                 listUser·p0.9999: 52.494 ms/op
                 listUser·p1.00:   52.494 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8527
  mean =      3.752 ±(99.9%) 0.099 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 8031 
    [ 5.000, 10.000) = 418 
    [10.000, 15.000) = 7 
    [15.000, 20.000) = 34 
    [20.000, 25.000) = 5 
    [25.000, 30.000) = 2 
    [30.000, 35.000) = 2 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 6 
    [45.000, 50.000) = 14 
    [50.000, 55.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.482 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      8.967 ms/op
     p(99.9000) =     45.941 ms/op
     p(99.9900) =     52.494 ms/op
     p(99.9990) =     52.494 ms/op
     p(99.9999) =     52.494 ms/op
    p(100.0000) =     52.494 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.307          ops/ms
ClientSimple.existUser                       thrpt         10.289          ops/ms
ClientSimple.getUser                         thrpt         11.029          ops/ms
ClientSimple.listUser                        thrpt          7.394          ops/ms
ClientSimple.createUser                       avgt          2.337           ms/op
ClientSimple.existUser                        avgt          1.987           ms/op
ClientSimple.getUser                          avgt          2.073           ms/op
ClientSimple.listUser                         avgt          4.199           ms/op
ClientSimple.createUser                     sample  12463   2.571 ± 0.053   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.549           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.281           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.056           ms/op
ClientSimple.createUser:createUser·p0.95    sample          4.108           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.748           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.054           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.017           ms/op
ClientSimple.createUser:createUser·p1.00    sample         28.049           ms/op
ClientSimple.existUser                      sample  15097   2.114 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.606           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.042           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.785           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.027           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.711           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.269           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.872           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.139           ms/op
ClientSimple.getUser                        sample  15145   2.109 ± 0.028   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.511           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.929           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.795           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.097           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.014           ms/op
ClientSimple.getUser:getUser·p0.999         sample         18.448           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.233           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.300           ms/op
ClientSimple.listUser                       sample   8527   3.752 ± 0.099   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.104           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.482           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.489           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.161           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.967           ms/op
ClientSimple.listUser:listUser·p0.999       sample         45.941           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         52.494           ms/op
ClientSimple.listUser:listUser·p1.00        sample         52.494           ms/op

Benchmark result is saved to 1725929170032.json
