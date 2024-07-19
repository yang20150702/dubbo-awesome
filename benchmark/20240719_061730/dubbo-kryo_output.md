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
# Warmup Iteration   1: 1.539 ops/ms
Iteration   1: 7.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.377 ops/ms


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
# Warmup Iteration   1: 5.194 ops/ms
Iteration   1: 11.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.112 ops/ms


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
# Warmup Iteration   1: 5.937 ops/ms
Iteration   1: 14.220 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.220 ops/ms


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
# Warmup Iteration   1: 5.472 ops/ms
Iteration   1: 8.456 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.456 ops/ms


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
# Warmup Iteration   1: 3.774 ±(99.9%) 0.063 ms/op
Iteration   1: 2.401 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.401 ms/op


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
# Warmup Iteration   1: 3.348 ±(99.9%) 0.050 ms/op
Iteration   1: 1.651 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.651 ms/op


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
# Warmup Iteration   1: 3.193 ±(99.9%) 0.054 ms/op
Iteration   1: 1.794 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.794 ms/op


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
# Warmup Iteration   1: 4.625 ±(99.9%) 0.103 ms/op
Iteration   1: 3.081 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.081 ms/op


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
# Warmup Iteration   1: 3.618 ±(99.9%) 0.100 ms/op
Iteration   1: 2.065 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.292 ms/op
                 createUser·p0.50:   1.929 ms/op
                 createUser·p0.90:   2.527 ms/op
                 createUser·p0.95:   2.765 ms/op
                 createUser·p0.99:   6.809 ms/op
                 createUser·p0.999:  15.221 ms/op
                 createUser·p0.9999: 16.687 ms/op
                 createUser·p1.00:   16.876 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15478
  mean =      2.065 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 366 
    [ 1.250,  2.500) = 13425 
    [ 2.500,  3.750) = 1369 
    [ 3.750,  5.000) = 117 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 43 
    [ 7.500,  8.750) = 63 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 14 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 28 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.292 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.765 ms/op
     p(99.0000) =      6.809 ms/op
     p(99.9000) =     15.221 ms/op
     p(99.9900) =     16.687 ms/op
     p(99.9990) =     16.876 ms/op
     p(99.9999) =     16.876 ms/op
    p(100.0000) =     16.876 ms/op


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
# Warmup Iteration   1: 3.072 ±(99.9%) 0.068 ms/op
Iteration   1: 1.998 ±(99.9%) 0.029 ms/op
                 existUser·p0.00:   0.506 ms/op
                 existUser·p0.50:   1.917 ms/op
                 existUser·p0.90:   2.388 ms/op
                 existUser·p0.95:   2.580 ms/op
                 existUser·p0.99:   2.896 ms/op
                 existUser·p0.999:  22.774 ms/op
                 existUser·p0.9999: 23.580 ms/op
                 existUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16000
  mean =      1.998 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14973 
    [ 2.500,  5.000) = 957 
    [ 5.000,  7.500) = 6 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.506 ms/op
     p(50.0000) =      1.917 ms/op
     p(90.0000) =      2.388 ms/op
     p(95.0000) =      2.580 ms/op
     p(99.0000) =      2.896 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     23.580 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 3.254 ±(99.9%) 0.087 ms/op
Iteration   1: 1.949 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.208 ms/op
                 getUser·p0.50:   1.853 ms/op
                 getUser·p0.90:   2.605 ms/op
                 getUser·p0.95:   2.773 ms/op
                 getUser·p0.99:   3.854 ms/op
                 getUser·p0.999:  16.220 ms/op
                 getUser·p0.9999: 16.396 ms/op
                 getUser·p1.00:   16.417 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16409
  mean =      1.949 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1377 
    [ 1.250,  2.500) = 12560 
    [ 2.500,  3.750) = 2293 
    [ 3.750,  5.000) = 114 
    [ 5.000,  6.250) = 33 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.208 ms/op
     p(50.0000) =      1.853 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.773 ms/op
     p(99.0000) =      3.854 ms/op
     p(99.9000) =     16.220 ms/op
     p(99.9900) =     16.396 ms/op
     p(99.9990) =     16.417 ms/op
     p(99.9999) =     16.417 ms/op
    p(100.0000) =     16.417 ms/op


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
# Warmup Iteration   1: 4.658 ±(99.9%) 0.209 ms/op
Iteration   1: 3.099 ±(99.9%) 0.046 ms/op
                 listUser·p0.00:   1.475 ms/op
                 listUser·p0.50:   2.810 ms/op
                 listUser·p0.90:   3.944 ms/op
                 listUser·p0.95:   4.293 ms/op
                 listUser·p0.99:   4.793 ms/op
                 listUser·p0.999:  26.870 ms/op
                 listUser·p0.9999: 27.981 ms/op
                 listUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10296
  mean =      3.099 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 431 
    [ 2.500,  5.000) = 9801 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      1.475 ms/op
     p(50.0000) =      2.810 ms/op
     p(90.0000) =      3.944 ms/op
     p(95.0000) =      4.293 ms/op
     p(99.0000) =      4.793 ms/op
     p(99.9000) =     26.870 ms/op
     p(99.9900) =     27.981 ms/op
     p(99.9990) =     27.984 ms/op
     p(99.9999) =     27.984 ms/op
    p(100.0000) =     27.984 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.377          ops/ms
ClientSimple.existUser                       thrpt         11.112          ops/ms
ClientSimple.getUser                         thrpt         14.220          ops/ms
ClientSimple.listUser                        thrpt          8.456          ops/ms
ClientSimple.createUser                       avgt          2.401           ms/op
ClientSimple.existUser                        avgt          1.651           ms/op
ClientSimple.getUser                          avgt          1.794           ms/op
ClientSimple.listUser                         avgt          3.081           ms/op
ClientSimple.createUser                     sample  15478   2.065 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.292           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.929           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.527           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.765           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.809           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.221           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.687           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.876           ms/op
ClientSimple.existUser                      sample  16000   1.998 ± 0.029   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.506           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.917           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.896           ms/op
ClientSimple.existUser:existUser·p0.999     sample         22.774           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         23.580           ms/op
ClientSimple.existUser:existUser·p1.00      sample         23.658           ms/op
ClientSimple.getUser                        sample  16409   1.949 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.208           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.853           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.605           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.773           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.854           ms/op
ClientSimple.getUser:getUser·p0.999         sample         16.220           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.396           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.417           ms/op
ClientSimple.listUser                       sample  10296   3.099 ± 0.046   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.475           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.810           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.944           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.293           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.793           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.870           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         27.981           ms/op
ClientSimple.listUser:listUser·p1.00        sample         27.984           ms/op

Benchmark result is saved to 1721369599611.json
