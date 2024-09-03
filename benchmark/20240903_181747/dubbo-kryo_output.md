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
# Warmup Iteration   1: 2.100 ops/ms
Iteration   1: 6.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.634 ops/ms


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
# Warmup Iteration   1: 5.385 ops/ms
Iteration   1: 12.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.022 ops/ms


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
# Warmup Iteration   1: 5.326 ops/ms
Iteration   1: 11.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.938 ops/ms


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
# Warmup Iteration   1: 4.736 ops/ms
Iteration   1: 9.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.216 ops/ms


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.080 ms/op
Iteration   1: 2.326 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.326 ms/op


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
# Warmup Iteration   1: 3.391 ±(99.9%) 0.044 ms/op
Iteration   1: 1.938 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.938 ms/op


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
# Warmup Iteration   1: 3.672 ±(99.9%) 0.068 ms/op
Iteration   1: 1.908 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.908 ms/op


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
# Warmup Iteration   1: 5.086 ±(99.9%) 0.098 ms/op
Iteration   1: 3.541 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.541 ms/op


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
# Warmup Iteration   1: 3.731 ±(99.9%) 0.105 ms/op
Iteration   1: 2.185 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.584 ms/op
                 createUser·p0.50:   1.951 ms/op
                 createUser·p0.90:   2.478 ms/op
                 createUser·p0.95:   2.822 ms/op
                 createUser·p0.99:   13.661 ms/op
                 createUser·p0.999:  24.261 ms/op
                 createUser·p0.9999: 24.790 ms/op
                 createUser·p1.00:   24.805 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14616
  mean =      2.185 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13267 
    [ 2.500,  5.000) = 1077 
    [ 5.000,  7.500) = 58 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 117 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.584 ms/op
     p(50.0000) =      1.951 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.822 ms/op
     p(99.0000) =     13.661 ms/op
     p(99.9000) =     24.261 ms/op
     p(99.9900) =     24.790 ms/op
     p(99.9990) =     24.805 ms/op
     p(99.9999) =     24.805 ms/op
    p(100.0000) =     24.805 ms/op


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
# Warmup Iteration   1: 3.203 ±(99.9%) 0.097 ms/op
Iteration   1: 1.924 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   1.784 ms/op
                 existUser·p0.90:   2.224 ms/op
                 existUser·p0.95:   2.462 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  18.361 ms/op
                 existUser·p0.9999: 20.054 ms/op
                 existUser·p1.00:   20.054 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16657
  mean =      1.924 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15917 
    [ 2.500,  5.000) = 651 
    [ 5.000,  7.500) = 20 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 4 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      1.784 ms/op
     p(90.0000) =      2.224 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =     18.361 ms/op
     p(99.9900) =     20.054 ms/op
     p(99.9990) =     20.054 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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
# Warmup Iteration   1: 3.331 ±(99.9%) 0.102 ms/op
Iteration   1: 2.029 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.510 ms/op
                 getUser·p0.50:   1.933 ms/op
                 getUser·p0.90:   2.527 ms/op
                 getUser·p0.95:   2.781 ms/op
                 getUser·p0.99:   4.420 ms/op
                 getUser·p0.999:  14.634 ms/op
                 getUser·p0.9999: 16.325 ms/op
                 getUser·p1.00:   16.335 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15841
  mean =      2.029 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 481 
    [ 1.250,  2.500) = 13662 
    [ 2.500,  3.750) = 1425 
    [ 3.750,  5.000) = 195 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 32 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 28 
    [15.000, 16.250) = 1 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.510 ms/op
     p(50.0000) =      1.933 ms/op
     p(90.0000) =      2.527 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      4.420 ms/op
     p(99.9000) =     14.634 ms/op
     p(99.9900) =     16.325 ms/op
     p(99.9990) =     16.335 ms/op
     p(99.9999) =     16.335 ms/op
    p(100.0000) =     16.335 ms/op


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
# Warmup Iteration   1: 5.092 ±(99.9%) 0.181 ms/op
Iteration   1: 3.632 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   1.077 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.496 ms/op
                 listUser·p0.95:   4.899 ms/op
                 listUser·p0.99:   6.713 ms/op
                 listUser·p0.999:  19.675 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8851
  mean =      3.632 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 407 
    [ 2.500,  5.000) = 8030 
    [ 5.000,  7.500) = 367 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.077 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.496 ms/op
     p(95.0000) =      4.899 ms/op
     p(99.0000) =      6.713 ms/op
     p(99.9000) =     19.675 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.634          ops/ms
ClientSimple.existUser                       thrpt         12.022          ops/ms
ClientSimple.getUser                         thrpt         11.938          ops/ms
ClientSimple.listUser                        thrpt          9.216          ops/ms
ClientSimple.createUser                       avgt          2.326           ms/op
ClientSimple.existUser                        avgt          1.938           ms/op
ClientSimple.getUser                          avgt          1.908           ms/op
ClientSimple.listUser                         avgt          3.541           ms/op
ClientSimple.createUser                     sample  14616   2.185 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.584           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.951           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.478           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.99    sample         13.661           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.261           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         24.790           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.805           ms/op
ClientSimple.existUser                      sample  16657   1.924 ± 0.024   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.784           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.784           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.224           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.462           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.260           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.361           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.054           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.054           ms/op
ClientSimple.getUser                        sample  15841   2.029 ± 0.022   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.510           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.933           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.527           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.781           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.420           ms/op
ClientSimple.getUser:getUser·p0.999         sample         14.634           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         16.325           ms/op
ClientSimple.getUser:getUser·p1.00          sample         16.335           ms/op
ClientSimple.listUser                       sample   8851   3.632 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.077           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.496           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.899           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.713           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.675           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.152           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.152           ms/op

Benchmark result is saved to 1725387219481.json
