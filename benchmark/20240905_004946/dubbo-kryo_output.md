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
# Warmup Iteration   1: 1.787 ops/ms
Iteration   1: 8.183 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.183 ops/ms


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
# Warmup Iteration   1: 5.475 ops/ms
Iteration   1: 12.848 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.848 ops/ms


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
# Warmup Iteration   1: 6.105 ops/ms
Iteration   1: 11.832 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.832 ops/ms


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
# Warmup Iteration   1: 4.759 ops/ms
Iteration   1: 8.600 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.600 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.069 ms/op
Iteration   1: 2.106 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.106 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 2.865 ±(99.9%) 0.043 ms/op
Iteration   1: 1.786 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.786 ms/op


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
# Warmup Iteration   1: 3.029 ±(99.9%) 0.050 ms/op
Iteration   1: 1.902 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.902 ms/op


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
# Warmup Iteration   1: 4.699 ±(99.9%) 0.088 ms/op
Iteration   1: 3.572 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.572 ms/op


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
# Warmup Iteration   1: 3.708 ±(99.9%) 0.084 ms/op
Iteration   1: 2.592 ±(99.9%) 0.050 ms/op
                 createUser·p0.00:   0.605 ms/op
                 createUser·p0.50:   2.335 ms/op
                 createUser·p0.90:   3.125 ms/op
                 createUser·p0.95:   3.529 ms/op
                 createUser·p0.99:   12.021 ms/op
                 createUser·p0.999:  18.842 ms/op
                 createUser·p0.9999: 19.106 ms/op
                 createUser·p1.00:   19.137 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12326
  mean =      2.592 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 7308 
    [ 2.500,  3.750) = 4454 
    [ 3.750,  5.000) = 122 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 45 
    [ 7.500,  8.750) = 40 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 27 
    [12.500, 13.750) = 41 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.605 ms/op
     p(50.0000) =      2.335 ms/op
     p(90.0000) =      3.125 ms/op
     p(95.0000) =      3.529 ms/op
     p(99.0000) =     12.021 ms/op
     p(99.9000) =     18.842 ms/op
     p(99.9900) =     19.106 ms/op
     p(99.9990) =     19.137 ms/op
     p(99.9999) =     19.137 ms/op
    p(100.0000) =     19.137 ms/op


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
# Warmup Iteration   1: 2.881 ±(99.9%) 0.068 ms/op
Iteration   1: 2.177 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.326 ms/op
                 existUser·p0.50:   2.071 ms/op
                 existUser·p0.90:   2.650 ms/op
                 existUser·p0.95:   2.851 ms/op
                 existUser·p0.99:   3.512 ms/op
                 existUser·p0.999:  18.645 ms/op
                 existUser·p0.9999: 22.451 ms/op
                 existUser·p1.00:   23.069 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14963
  mean =      2.177 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11847 
    [ 2.500,  5.000) = 3023 
    [ 5.000,  7.500) = 29 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      3.512 ms/op
     p(99.9000) =     18.645 ms/op
     p(99.9900) =     22.451 ms/op
     p(99.9990) =     23.069 ms/op
     p(99.9999) =     23.069 ms/op
    p(100.0000) =     23.069 ms/op


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
# Warmup Iteration   1: 3.552 ±(99.9%) 0.090 ms/op
Iteration   1: 2.092 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.017 ms/op
                 getUser·p0.90:   2.691 ms/op
                 getUser·p0.95:   2.966 ms/op
                 getUser·p0.99:   3.819 ms/op
                 getUser·p0.999:  10.748 ms/op
                 getUser·p0.9999: 11.687 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15473
  mean =      2.092 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 12821 
    [ 2.500,  3.750) = 2330 
    [ 3.750,  5.000) = 83 
    [ 5.000,  6.250) = 26 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 9 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.017 ms/op
     p(90.0000) =      2.691 ms/op
     p(95.0000) =      2.966 ms/op
     p(99.0000) =      3.819 ms/op
     p(99.9000) =     10.748 ms/op
     p(99.9900) =     11.687 ms/op
     p(99.9990) =     11.911 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.157 ms/op
Iteration   1: 3.078 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   1.223 ms/op
                 listUser·p0.50:   2.757 ms/op
                 listUser·p0.90:   3.977 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.948 ms/op
                 listUser·p0.999:  17.212 ms/op
                 listUser·p0.9999: 17.530 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10391
  mean =      3.078 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1 
    [ 1.250,  2.500) = 1203 
    [ 2.500,  3.750) = 7436 
    [ 3.750,  5.000) = 1596 
    [ 5.000,  6.250) = 83 
    [ 6.250,  7.500) = 40 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.223 ms/op
     p(50.0000) =      2.757 ms/op
     p(90.0000) =      3.977 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.948 ms/op
     p(99.9000) =     17.212 ms/op
     p(99.9900) =     17.530 ms/op
     p(99.9990) =     17.531 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.183          ops/ms
ClientSimple.existUser                       thrpt         12.848          ops/ms
ClientSimple.getUser                         thrpt         11.832          ops/ms
ClientSimple.listUser                        thrpt          8.600          ops/ms
ClientSimple.createUser                       avgt          2.106           ms/op
ClientSimple.existUser                        avgt          1.786           ms/op
ClientSimple.getUser                          avgt          1.902           ms/op
ClientSimple.listUser                         avgt          3.572           ms/op
ClientSimple.createUser                     sample  12326   2.592 ± 0.050   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.605           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.335           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.125           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.529           ms/op
ClientSimple.createUser:createUser·p0.99    sample         12.021           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.842           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.106           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.137           ms/op
ClientSimple.existUser                      sample  14963   2.177 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.326           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.071           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.650           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.851           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.512           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.645           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.451           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.069           ms/op
ClientSimple.getUser                        sample  15473   2.092 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.568           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.017           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.691           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.966           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.819           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.748           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.687           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.911           ms/op
ClientSimple.listUser                       sample  10391   3.078 ± 0.033   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.223           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.757           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.977           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.948           ms/op
ClientSimple.listUser:listUser·p0.999       sample         17.212           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         17.530           ms/op
ClientSimple.listUser:listUser·p1.00        sample         17.531           ms/op

Benchmark result is saved to 1725497130497.json
