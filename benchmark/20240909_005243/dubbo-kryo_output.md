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
# Warmup Iteration   1: 1.267 ops/ms
Iteration   1: 5.532 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.532 ops/ms


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
# Warmup Iteration   1: 5.223 ops/ms
Iteration   1: 11.634 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.634 ops/ms


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
# Warmup Iteration   1: 5.122 ops/ms
Iteration   1: 12.395 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.395 ops/ms


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
# Warmup Iteration   1: 4.960 ops/ms
Iteration   1: 8.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.298 ops/ms


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
# Warmup Iteration   1: 5.273 ±(99.9%) 0.125 ms/op
Iteration   1: 2.376 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.376 ms/op


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
# Warmup Iteration   1: 3.202 ±(99.9%) 0.059 ms/op
Iteration   1: 1.932 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.932 ms/op


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
# Warmup Iteration   1: 3.485 ±(99.9%) 0.067 ms/op
Iteration   1: 2.057 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.057 ms/op


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
# Warmup Iteration   1: 4.300 ±(99.9%) 0.070 ms/op
Iteration   1: 2.864 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.864 ms/op


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
# Warmup Iteration   1: 3.594 ±(99.9%) 0.097 ms/op
Iteration   1: 2.240 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.801 ms/op
                 createUser·p0.50:   1.991 ms/op
                 createUser·p0.90:   2.626 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  23.091 ms/op
                 createUser·p0.9999: 25.062 ms/op
                 createUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14304
  mean =      2.240 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12407 
    [ 2.500,  5.000) = 1662 
    [ 5.000,  7.500) = 96 
    [ 7.500, 10.000) = 43 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.801 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.626 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     23.091 ms/op
     p(99.9900) =     25.062 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


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
# Warmup Iteration   1: 3.091 ±(99.9%) 0.071 ms/op
Iteration   1: 1.842 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   1.706 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.445 ms/op
                 existUser·p0.99:   3.221 ms/op
                 existUser·p0.999:  20.075 ms/op
                 existUser·p0.9999: 20.218 ms/op
                 existUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17373
  mean =      1.842 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16666 
    [ 2.500,  5.000) = 643 
    [ 5.000,  7.500) = 0 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.706 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.445 ms/op
     p(99.0000) =      3.221 ms/op
     p(99.9000) =     20.075 ms/op
     p(99.9900) =     20.218 ms/op
     p(99.9990) =     20.218 ms/op
     p(99.9999) =     20.218 ms/op
    p(100.0000) =     20.218 ms/op


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
# Warmup Iteration   1: 3.663 ±(99.9%) 0.102 ms/op
Iteration   1: 2.134 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   0.816 ms/op
                 getUser·p0.50:   1.927 ms/op
                 getUser·p0.90:   2.871 ms/op
                 getUser·p0.95:   3.039 ms/op
                 getUser·p0.99:   3.420 ms/op
                 getUser·p0.999:  13.072 ms/op
                 getUser·p0.9999: 13.328 ms/op
                 getUser·p1.00:   13.337 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15133
  mean =      2.134 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 90 
    [ 1.250,  2.500) = 11898 
    [ 2.500,  3.750) = 3070 
    [ 3.750,  5.000) = 17 
    [ 5.000,  6.250) = 23 
    [ 6.250,  7.500) = 3 
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
      p(0.0000) =      0.816 ms/op
     p(50.0000) =      1.927 ms/op
     p(90.0000) =      2.871 ms/op
     p(95.0000) =      3.039 ms/op
     p(99.0000) =      3.420 ms/op
     p(99.9000) =     13.072 ms/op
     p(99.9900) =     13.328 ms/op
     p(99.9990) =     13.337 ms/op
     p(99.9999) =     13.337 ms/op
    p(100.0000) =     13.337 ms/op


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
# Warmup Iteration   1: 4.665 ±(99.9%) 0.125 ms/op
Iteration   1: 3.242 ±(99.9%) 0.048 ms/op
                 listUser·p0.00:   0.692 ms/op
                 listUser·p0.50:   2.875 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.641 ms/op
                 listUser·p0.99:   7.020 ms/op
                 listUser·p0.999:  24.613 ms/op
                 listUser·p0.9999: 24.871 ms/op
                 listUser·p1.00:   24.871 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9869
  mean =      3.242 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 732 
    [ 2.500,  5.000) = 8784 
    [ 5.000,  7.500) = 278 
    [ 7.500, 10.000) = 41 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      2.875 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.641 ms/op
     p(99.0000) =      7.020 ms/op
     p(99.9000) =     24.613 ms/op
     p(99.9900) =     24.871 ms/op
     p(99.9990) =     24.871 ms/op
     p(99.9999) =     24.871 ms/op
    p(100.0000) =     24.871 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.532          ops/ms
ClientSimple.existUser                       thrpt         11.634          ops/ms
ClientSimple.getUser                         thrpt         12.395          ops/ms
ClientSimple.listUser                        thrpt          8.298          ops/ms
ClientSimple.createUser                       avgt          2.376           ms/op
ClientSimple.existUser                        avgt          1.932           ms/op
ClientSimple.getUser                          avgt          2.057           ms/op
ClientSimple.listUser                         avgt          2.864           ms/op
ClientSimple.createUser                     sample  14304   2.240 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.801           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.991           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.626           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.225           ms/op
ClientSimple.createUser:createUser·p0.999   sample         23.091           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         25.062           ms/op
ClientSimple.createUser:createUser·p1.00    sample         25.231           ms/op
ClientSimple.existUser                      sample  17373   1.842 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.660           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.706           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.445           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.221           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.075           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.218           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.218           ms/op
ClientSimple.getUser                        sample  15133   2.134 ± 0.019   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.816           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.927           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.871           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.039           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.420           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.072           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.328           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.337           ms/op
ClientSimple.listUser                       sample   9869   3.242 ± 0.048   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.692           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.875           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.284           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.641           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.020           ms/op
ClientSimple.listUser:listUser·p0.999       sample         24.613           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.871           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.871           ms/op

Benchmark result is saved to 1725842905201.json
