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
# Warmup Iteration   1: 2.041 ops/ms
Iteration   1: 7.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.565 ops/ms


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
# Warmup Iteration   1: 5.400 ops/ms
Iteration   1: 12.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.537 ops/ms


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
# Warmup Iteration   1: 5.807 ops/ms
Iteration   1: 14.199 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.199 ops/ms


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
# Warmup Iteration   1: 5.418 ops/ms
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
# Warmup Iteration   1: 3.850 ±(99.9%) 0.065 ms/op
Iteration   1: 2.059 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.059 ms/op


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
# Warmup Iteration   1: 3.139 ±(99.9%) 0.061 ms/op
Iteration   1: 1.833 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.833 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.053 ms/op
Iteration   1: 2.159 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.159 ms/op


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
# Warmup Iteration   1: 4.240 ±(99.9%) 0.084 ms/op
Iteration   1: 3.281 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.281 ms/op


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
# Warmup Iteration   1: 3.360 ±(99.9%) 0.078 ms/op
Iteration   1: 2.122 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   1.987 ms/op
                 createUser·p0.90:   2.621 ms/op
                 createUser·p0.95:   2.810 ms/op
                 createUser·p0.99:   5.146 ms/op
                 createUser·p0.999:  15.941 ms/op
                 createUser·p0.9999: 16.974 ms/op
                 createUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15058
  mean =      2.122 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 315 
    [ 1.250,  2.500) = 12483 
    [ 2.500,  3.750) = 2046 
    [ 3.750,  5.000) = 46 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 25 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 10 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      1.987 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      5.146 ms/op
     p(99.9000) =     15.941 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


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
# Warmup Iteration   1: 3.197 ±(99.9%) 0.098 ms/op
Iteration   1: 2.174 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.627 ms/op
                 existUser·p0.50:   2.042 ms/op
                 existUser·p0.90:   2.617 ms/op
                 existUser·p0.95:   2.802 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  22.708 ms/op
                 existUser·p0.9999: 22.807 ms/op
                 existUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14706
  mean =      2.174 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12593 
    [ 2.500,  5.000) = 1978 
    [ 5.000,  7.500) = 70 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 7 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.627 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.802 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =     22.708 ms/op
     p(99.9900) =     22.807 ms/op
     p(99.9990) =     22.807 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 3.315 ±(99.9%) 0.081 ms/op
Iteration   1: 2.022 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.629 ms/op
                 getUser·p0.50:   1.950 ms/op
                 getUser·p0.90:   2.568 ms/op
                 getUser·p0.95:   2.748 ms/op
                 getUser·p0.99:   3.666 ms/op
                 getUser·p0.999:  10.676 ms/op
                 getUser·p0.9999: 11.115 ms/op
                 getUser·p1.00:   11.125 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15798
  mean =      2.022 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 152 
    [ 1.250,  2.500) = 13706 
    [ 2.500,  3.750) = 1788 
    [ 3.750,  5.000) = 66 
    [ 5.000,  6.250) = 54 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.629 ms/op
     p(50.0000) =      1.950 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.666 ms/op
     p(99.9000) =     10.676 ms/op
     p(99.9900) =     11.115 ms/op
     p(99.9990) =     11.125 ms/op
     p(99.9999) =     11.125 ms/op
    p(100.0000) =     11.125 ms/op


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.166 ms/op
Iteration   1: 3.534 ±(99.9%) 0.050 ms/op
                 listUser·p0.00:   1.206 ms/op
                 listUser·p0.50:   3.514 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.522 ms/op
                 listUser·p0.99:   5.906 ms/op
                 listUser·p0.999:  25.131 ms/op
                 listUser·p0.9999: 25.625 ms/op
                 listUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9049
  mean =      3.534 ±(99.9%) 0.050 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1022 
    [ 2.500,  5.000) = 7802 
    [ 5.000,  7.500) = 155 
    [ 7.500, 10.000) = 35 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.514 ms/op
     p(90.0000) =      4.268 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      5.906 ms/op
     p(99.9000) =     25.131 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     25.625 ms/op
     p(99.9999) =     25.625 ms/op
    p(100.0000) =     25.625 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.565          ops/ms
ClientSimple.existUser                       thrpt         12.537          ops/ms
ClientSimple.getUser                         thrpt         14.199          ops/ms
ClientSimple.listUser                        thrpt          8.079          ops/ms
ClientSimple.createUser                       avgt          2.059           ms/op
ClientSimple.existUser                        avgt          1.833           ms/op
ClientSimple.getUser                          avgt          2.159           ms/op
ClientSimple.listUser                         avgt          3.281           ms/op
ClientSimple.createUser                     sample  15058   2.122 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.457           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.987           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.621           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.810           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.146           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.941           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.974           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.974           ms/op
ClientSimple.existUser                      sample  14706   2.174 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.627           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.042           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.617           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.802           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.702           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.708           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.807           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.807           ms/op
ClientSimple.getUser                        sample  15798   2.022 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.629           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.950           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.748           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.666           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.676           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.115           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.125           ms/op
ClientSimple.listUser                       sample   9049   3.534 ± 0.050   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.206           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.514           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.268           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.522           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.906           ms/op
ClientSimple.listUser:listUser·p0.999       sample         25.131           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         25.625           ms/op
ClientSimple.listUser:listUser·p1.00        sample         25.625           ms/op

Benchmark result is saved to 1721499110301.json
