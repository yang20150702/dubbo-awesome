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
# Warmup Iteration   1: 1.807 ops/ms
Iteration   1: 7.275 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.275 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.401 ops/ms
Iteration   1: 12.788 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.788 ops/ms


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
# Warmup Iteration   1: 5.958 ops/ms
Iteration   1: 12.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.200 ops/ms


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
# Warmup Iteration   1: 5.499 ops/ms
Iteration   1: 8.544 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.544 ops/ms


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
# Warmup Iteration   1: 4.438 ±(99.9%) 0.114 ms/op
Iteration   1: 2.210 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.210 ms/op


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
# Warmup Iteration   1: 4.102 ±(99.9%) 0.095 ms/op
Iteration   1: 2.086 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.086 ms/op


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
# Warmup Iteration   1: 3.727 ±(99.9%) 0.073 ms/op
Iteration   1: 1.960 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.960 ms/op


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
# Warmup Iteration   1: 4.274 ±(99.9%) 0.096 ms/op
Iteration   1: 3.275 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.275 ms/op


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
# Warmup Iteration   1: 4.288 ±(99.9%) 0.095 ms/op
Iteration   1: 2.200 ±(99.9%) 0.034 ms/op
                 createUser·p0.00:   0.657 ms/op
                 createUser·p0.50:   2.017 ms/op
                 createUser·p0.90:   2.597 ms/op
                 createUser·p0.95:   2.909 ms/op
                 createUser·p0.99:   7.730 ms/op
                 createUser·p0.999:  17.907 ms/op
                 createUser·p0.9999: 18.800 ms/op
                 createUser·p1.00:   19.038 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14535
  mean =      2.200 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 12490 
    [ 2.500,  3.750) = 1658 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 44 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 49 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 29 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.657 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.597 ms/op
     p(95.0000) =      2.909 ms/op
     p(99.0000) =      7.730 ms/op
     p(99.9000) =     17.907 ms/op
     p(99.9900) =     18.800 ms/op
     p(99.9990) =     19.038 ms/op
     p(99.9999) =     19.038 ms/op
    p(100.0000) =     19.038 ms/op


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
# Warmup Iteration   1: 3.112 ±(99.9%) 0.065 ms/op
Iteration   1: 2.269 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.283 ms/op
                 existUser·p0.50:   2.191 ms/op
                 existUser·p0.90:   2.748 ms/op
                 existUser·p0.95:   2.933 ms/op
                 existUser·p0.99:   4.606 ms/op
                 existUser·p0.999:  18.219 ms/op
                 existUser·p0.9999: 18.323 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14088
  mean =      2.269 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 229 
    [ 1.250,  2.500) = 10368 
    [ 2.500,  3.750) = 3293 
    [ 3.750,  5.000) = 74 
    [ 5.000,  6.250) = 42 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 8 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 23 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.283 ms/op
     p(50.0000) =      2.191 ms/op
     p(90.0000) =      2.748 ms/op
     p(95.0000) =      2.933 ms/op
     p(99.0000) =      4.606 ms/op
     p(99.9000) =     18.219 ms/op
     p(99.9900) =     18.323 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 3.478 ±(99.9%) 0.098 ms/op
Iteration   1: 1.882 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.556 ms/op
                 getUser·p0.50:   1.796 ms/op
                 getUser·p0.90:   2.421 ms/op
                 getUser·p0.95:   2.593 ms/op
                 getUser·p0.99:   3.101 ms/op
                 getUser·p0.999:  13.075 ms/op
                 getUser·p0.9999: 13.517 ms/op
                 getUser·p1.00:   13.517 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16994
  mean =      1.882 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 666 
    [ 1.250,  2.500) = 15097 
    [ 2.500,  3.750) = 1161 
    [ 3.750,  5.000) = 20 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 11 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      1.796 ms/op
     p(90.0000) =      2.421 ms/op
     p(95.0000) =      2.593 ms/op
     p(99.0000) =      3.101 ms/op
     p(99.9000) =     13.075 ms/op
     p(99.9900) =     13.517 ms/op
     p(99.9990) =     13.517 ms/op
     p(99.9999) =     13.517 ms/op
    p(100.0000) =     13.517 ms/op


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
# Warmup Iteration   1: 4.833 ±(99.9%) 0.168 ms/op
Iteration   1: 3.260 ±(99.9%) 0.041 ms/op
                 listUser·p0.00:   1.073 ms/op
                 listUser·p0.50:   2.933 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.727 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9826
  mean =      3.260 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1514 
    [ 2.500,  5.000) = 7924 
    [ 5.000,  7.500) = 278 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.727 ms/op
     p(99.0000) =      7.651 ms/op
     p(99.9000) =     17.662 ms/op
     p(99.9900) =     20.382 ms/op
     p(99.9990) =     20.382 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.275          ops/ms
ClientSimple.existUser                       thrpt         12.788          ops/ms
ClientSimple.getUser                         thrpt         12.200          ops/ms
ClientSimple.listUser                        thrpt          8.544          ops/ms
ClientSimple.createUser                       avgt          2.210           ms/op
ClientSimple.existUser                        avgt          2.086           ms/op
ClientSimple.getUser                          avgt          1.960           ms/op
ClientSimple.listUser                         avgt          3.275           ms/op
ClientSimple.createUser                     sample  14535   2.200 ± 0.034   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.657           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.017           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.597           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.909           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.730           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.907           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.800           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.038           ms/op
ClientSimple.existUser                      sample  14088   2.269 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.283           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.191           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.933           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.606           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.219           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.323           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.350           ms/op
ClientSimple.getUser                        sample  16994   1.882 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.556           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.796           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.421           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.101           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.075           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.517           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.517           ms/op
ClientSimple.listUser                       sample   9826   3.260 ± 0.041   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.073           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.933           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.727           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.651           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.662           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.382           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.382           ms/op

Benchmark result is saved to 1723659170632.json
