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
# Warmup Iteration   1: 1.592 ops/ms
Iteration   1: 6.329 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.329 ops/ms


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
# Warmup Iteration   1: 5.886 ops/ms
Iteration   1: 12.370 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.370 ops/ms


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
# Warmup Iteration   1: 4.785 ops/ms
Iteration   1: 9.895 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  9.895 ops/ms


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
# Warmup Iteration   1: 4.257 ops/ms
Iteration   1: 9.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.129 ops/ms


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
# Warmup Iteration   1: 4.343 ±(99.9%) 0.082 ms/op
Iteration   1: 2.336 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.336 ms/op


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
# Warmup Iteration   1: 3.828 ±(99.9%) 0.068 ms/op
Iteration   1: 2.190 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.190 ms/op


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
# Warmup Iteration   1: 3.572 ±(99.9%) 0.070 ms/op
Iteration   1: 1.963 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.963 ms/op


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
# Warmup Iteration   1: 4.785 ±(99.9%) 0.101 ms/op
Iteration   1: 3.502 ±(99.9%) 0.013 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.420 ±(99.9%) 0.078 ms/op
Iteration   1: 2.282 ±(99.9%) 0.055 ms/op
                 createUser·p0.00:   0.330 ms/op
                 createUser·p0.50:   1.968 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.338 ms/op
                 createUser·p0.99:   10.321 ms/op
                 createUser·p0.999:  30.141 ms/op
                 createUser·p0.9999: 32.426 ms/op
                 createUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14051
  mean =      2.282 ±(99.9%) 0.055 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11632 
    [ 2.500,  5.000) = 2045 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 111 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.330 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.338 ms/op
     p(99.0000) =     10.321 ms/op
     p(99.9000) =     30.141 ms/op
     p(99.9900) =     32.426 ms/op
     p(99.9990) =     32.506 ms/op
     p(99.9999) =     32.506 ms/op
    p(100.0000) =     32.506 ms/op


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
# Warmup Iteration   1: 3.382 ±(99.9%) 0.101 ms/op
Iteration   1: 2.019 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.807 ms/op
                 existUser·p0.50:   1.960 ms/op
                 existUser·p0.90:   2.466 ms/op
                 existUser·p0.95:   2.810 ms/op
                 existUser·p0.99:   3.676 ms/op
                 existUser·p0.999:  11.256 ms/op
                 existUser·p0.9999: 11.777 ms/op
                 existUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15841
  mean =      2.019 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 237 
    [ 1.250,  2.500) = 14159 
    [ 2.500,  3.750) = 1293 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 24 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 16 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      1.960 ms/op
     p(90.0000) =      2.466 ms/op
     p(95.0000) =      2.810 ms/op
     p(99.0000) =      3.676 ms/op
     p(99.9000) =     11.256 ms/op
     p(99.9900) =     11.777 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.437 ±(99.9%) 0.104 ms/op
Iteration   1: 2.036 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   1.884 ms/op
                 getUser·p0.90:   2.621 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   3.947 ms/op
                 getUser·p0.999:  22.189 ms/op
                 getUser·p0.9999: 22.924 ms/op
                 getUser·p1.00:   23.036 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15707
  mean =      2.036 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13429 
    [ 2.500,  5.000) = 2164 
    [ 5.000,  7.500) = 49 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.884 ms/op
     p(90.0000) =      2.621 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      3.947 ms/op
     p(99.9000) =     22.189 ms/op
     p(99.9900) =     22.924 ms/op
     p(99.9990) =     23.036 ms/op
     p(99.9999) =     23.036 ms/op
    p(100.0000) =     23.036 ms/op


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
# Warmup Iteration   1: 4.518 ±(99.9%) 0.135 ms/op
Iteration   1: 3.298 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   0.857 ms/op
                 listUser·p0.50:   3.228 ms/op
                 listUser·p0.90:   4.104 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.807 ms/op
                 listUser·p0.999:  19.195 ms/op
                 listUser·p0.9999: 22.118 ms/op
                 listUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9700
  mean =      3.298 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2092 
    [ 2.500,  5.000) = 7351 
    [ 5.000,  7.500) = 138 
    [ 7.500, 10.000) = 39 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.857 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      4.104 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     19.195 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.329          ops/ms
ClientSimple.existUser                       thrpt         12.370          ops/ms
ClientSimple.getUser                         thrpt          9.895          ops/ms
ClientSimple.listUser                        thrpt          9.129          ops/ms
ClientSimple.createUser                       avgt          2.336           ms/op
ClientSimple.existUser                        avgt          2.190           ms/op
ClientSimple.getUser                          avgt          1.963           ms/op
ClientSimple.listUser                         avgt          3.502           ms/op
ClientSimple.createUser                     sample  14051   2.282 ± 0.055   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.330           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.968           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.338           ms/op
ClientSimple.createUser:createUser·p0.99    sample         10.321           ms/op
ClientSimple.createUser:createUser·p0.999   sample         30.141           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.426           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.506           ms/op
ClientSimple.existUser                      sample  15841   2.019 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.807           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.960           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.466           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.810           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.676           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.256           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.777           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.911           ms/op
ClientSimple.getUser                        sample  15707   2.036 ± 0.033   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.647           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.884           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.621           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.947           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.189           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.924           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.036           ms/op
ClientSimple.listUser                       sample   9700   3.298 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.857           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.228           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.104           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.530           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.807           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.195           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.118           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.118           ms/op

Benchmark result is saved to 1725152091716.json
