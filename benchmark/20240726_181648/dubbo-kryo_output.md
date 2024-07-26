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
# Warmup Iteration   1: 1.731 ops/ms
Iteration   1: 6.931 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.931 ops/ms


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
# Warmup Iteration   1: 6.434 ops/ms
Iteration   1: 13.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.876 ops/ms


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
# Warmup Iteration   1: 5.695 ops/ms
Iteration   1: 12.013 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.013 ops/ms


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
# Warmup Iteration   1: 3.988 ops/ms
Iteration   1: 8.048 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.048 ops/ms


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
# Warmup Iteration   1: 3.986 ±(99.9%) 0.072 ms/op
Iteration   1: 2.141 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.141 ms/op


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
# Warmup Iteration   1: 3.589 ±(99.9%) 0.055 ms/op
Iteration   1: 1.785 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.785 ms/op


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
# Warmup Iteration   1: 3.688 ±(99.9%) 0.065 ms/op
Iteration   1: 2.302 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.302 ms/op


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
# Warmup Iteration   1: 4.550 ±(99.9%) 0.106 ms/op
Iteration   1: 3.170 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.170 ms/op


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
# Warmup Iteration   1: 3.385 ±(99.9%) 0.081 ms/op
Iteration   1: 2.176 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   2.109 ms/op
                 createUser·p0.90:   2.703 ms/op
                 createUser·p0.95:   2.908 ms/op
                 createUser·p0.99:   3.408 ms/op
                 createUser·p0.999:  14.746 ms/op
                 createUser·p0.9999: 15.979 ms/op
                 createUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14720
  mean =      2.176 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 274 
    [ 1.250,  2.500) = 11314 
    [ 2.500,  3.750) = 3034 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 10 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 22 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 8 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.908 ms/op
     p(99.0000) =      3.408 ms/op
     p(99.9000) =     14.746 ms/op
     p(99.9900) =     15.979 ms/op
     p(99.9990) =     16.056 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 2.945 ±(99.9%) 0.066 ms/op
Iteration   1: 1.872 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.814 ms/op
                 existUser·p0.50:   1.765 ms/op
                 existUser·p0.90:   2.013 ms/op
                 existUser·p0.95:   2.232 ms/op
                 existUser·p0.99:   3.564 ms/op
                 existUser·p0.999:  16.220 ms/op
                 existUser·p0.9999: 16.600 ms/op
                 existUser·p1.00:   16.646 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17096
  mean =      1.872 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 16566 
    [ 2.500,  3.750) = 303 
    [ 3.750,  5.000) = 42 
    [ 5.000,  6.250) = 13 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 16 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 50 
    [16.250, 17.500) = 13 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.814 ms/op
     p(50.0000) =      1.765 ms/op
     p(90.0000) =      2.013 ms/op
     p(95.0000) =      2.232 ms/op
     p(99.0000) =      3.564 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     16.600 ms/op
     p(99.9990) =     16.646 ms/op
     p(99.9999) =     16.646 ms/op
    p(100.0000) =     16.646 ms/op


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
Iteration   1: 1.994 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.722 ms/op
                 getUser·p0.50:   1.829 ms/op
                 getUser·p0.90:   2.474 ms/op
                 getUser·p0.95:   2.712 ms/op
                 getUser·p0.99:   4.112 ms/op
                 getUser·p0.999:  15.581 ms/op
                 getUser·p0.9999: 17.727 ms/op
                 getUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16022
  mean =      1.994 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 62 
    [ 1.250,  2.500) = 14480 
    [ 2.500,  3.750) = 1268 
    [ 3.750,  5.000) = 161 
    [ 5.000,  6.250) = 17 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.722 ms/op
     p(50.0000) =      1.829 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      2.712 ms/op
     p(99.0000) =      4.112 ms/op
     p(99.9000) =     15.581 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


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
# Warmup Iteration   1: 4.350 ±(99.9%) 0.129 ms/op
Iteration   1: 3.445 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   1.094 ms/op
                 listUser·p0.50:   3.531 ms/op
                 listUser·p0.90:   4.112 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   5.515 ms/op
                 listUser·p0.999:  7.324 ms/op
                 listUser·p0.9999: 7.856 ms/op
                 listUser·p1.00:   7.856 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9281
  mean =      3.445 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [1.000, 1.500) = 15 
    [1.500, 2.000) = 57 
    [2.000, 2.500) = 440 
    [2.500, 3.000) = 2064 
    [3.000, 3.500) = 1876 
    [3.500, 4.000) = 3461 
    [4.000, 4.500) = 1108 
    [4.500, 5.000) = 128 
    [5.000, 5.500) = 35 
    [5.500, 6.000) = 58 
    [6.000, 6.500) = 1 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.094 ms/op
     p(50.0000) =      3.531 ms/op
     p(90.0000) =      4.112 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =      5.515 ms/op
     p(99.9000) =      7.324 ms/op
     p(99.9900) =      7.856 ms/op
     p(99.9990) =      7.856 ms/op
     p(99.9999) =      7.856 ms/op
    p(100.0000) =      7.856 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.931          ops/ms
ClientSimple.existUser                       thrpt         13.876          ops/ms
ClientSimple.getUser                         thrpt         12.013          ops/ms
ClientSimple.listUser                        thrpt          8.048          ops/ms
ClientSimple.createUser                       avgt          2.141           ms/op
ClientSimple.existUser                        avgt          1.785           ms/op
ClientSimple.getUser                          avgt          2.302           ms/op
ClientSimple.listUser                         avgt          3.170           ms/op
ClientSimple.createUser                     sample  14720   2.176 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.584           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.109           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.703           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.908           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.408           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.746           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         15.979           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.056           ms/op
ClientSimple.existUser                      sample  17096   1.872 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.814           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.765           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.013           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.232           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.564           ms/op
ClientSimple.existUser:existUser·p0.999     sample         16.220           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         16.600           ms/op
ClientSimple.existUser:existUser·p1.00      sample         16.646           ms/op
ClientSimple.getUser                        sample  16022   1.994 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.722           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.829           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.474           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.112           ms/op
ClientSimple.getUser:getUser·p0.999         sample         15.581           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         17.727           ms/op
ClientSimple.getUser:getUser·p1.00          sample         17.924           ms/op
ClientSimple.listUser                       sample   9281   3.445 ± 0.023   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.094           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.531           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.112           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.334           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.515           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.324           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          7.856           ms/op
ClientSimple.listUser:listUser·p1.00        sample          7.856           ms/op

Benchmark result is saved to 1722017550631.json
