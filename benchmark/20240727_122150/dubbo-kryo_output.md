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
# Warmup Iteration   1: 1.854 ops/ms
Iteration   1: 6.654 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.654 ops/ms


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
# Warmup Iteration   1: 5.581 ops/ms
Iteration   1: 12.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.784 ops/ms


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
# Warmup Iteration   1: 5.802 ops/ms
Iteration   1: 13.668 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.668 ops/ms


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
# Warmup Iteration   1: 4.952 ops/ms
Iteration   1: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.398 ops/ms


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
# Warmup Iteration   1: 3.953 ±(99.9%) 0.081 ms/op
Iteration   1: 2.187 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.187 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.053 ms/op
Iteration   1: 1.789 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.789 ms/op


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
# Warmup Iteration   1: 3.185 ±(99.9%) 0.050 ms/op
Iteration   1: 2.118 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.118 ms/op


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
# Warmup Iteration   1: 4.646 ±(99.9%) 0.091 ms/op
Iteration   1: 3.501 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.501 ms/op


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
# Warmup Iteration   1: 3.734 ±(99.9%) 0.108 ms/op
Iteration   1: 2.220 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.489 ms/op
                 createUser·p0.50:   2.097 ms/op
                 createUser·p0.90:   2.822 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   4.202 ms/op
                 createUser·p0.999:  12.714 ms/op
                 createUser·p0.9999: 13.002 ms/op
                 createUser·p1.00:   13.009 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14374
  mean =      2.220 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 10392 
    [ 2.500,  3.750) = 3638 
    [ 3.750,  5.000) = 133 
    [ 5.000,  6.250) = 40 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.489 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.822 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =     12.714 ms/op
     p(99.9900) =     13.002 ms/op
     p(99.9990) =     13.009 ms/op
     p(99.9999) =     13.009 ms/op
    p(100.0000) =     13.009 ms/op


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
# Warmup Iteration   1: 2.919 ±(99.9%) 0.067 ms/op
Iteration   1: 1.804 ±(99.9%) 0.044 ms/op
                 existUser·p0.00:   0.339 ms/op
                 existUser·p0.50:   1.577 ms/op
                 existUser·p0.90:   2.154 ms/op
                 existUser·p0.95:   2.400 ms/op
                 existUser·p0.99:   5.188 ms/op
                 existUser·p0.999:  40.698 ms/op
                 existUser·p0.9999: 41.327 ms/op
                 existUser·p1.00:   41.943 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17835
  mean =      1.804 ±(99.9%) 0.044 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 17652 
    [ 5.000, 10.000) = 118 
    [10.000, 15.000) = 33 
    [15.000, 20.000) = 0 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.339 ms/op
     p(50.0000) =      1.577 ms/op
     p(90.0000) =      2.154 ms/op
     p(95.0000) =      2.400 ms/op
     p(99.0000) =      5.188 ms/op
     p(99.9000) =     40.698 ms/op
     p(99.9900) =     41.327 ms/op
     p(99.9990) =     41.943 ms/op
     p(99.9999) =     41.943 ms/op
    p(100.0000) =     41.943 ms/op


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
# Warmup Iteration   1: 3.186 ±(99.9%) 0.098 ms/op
Iteration   1: 1.879 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.359 ms/op
                 getUser·p0.50:   1.745 ms/op
                 getUser·p0.90:   2.363 ms/op
                 getUser·p0.95:   2.556 ms/op
                 getUser·p0.99:   4.049 ms/op
                 getUser·p0.999:  12.960 ms/op
                 getUser·p0.9999: 13.412 ms/op
                 getUser·p1.00:   13.435 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17050
  mean =      1.879 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 690 
    [ 1.250,  2.500) = 15346 
    [ 2.500,  3.750) = 799 
    [ 3.750,  5.000) = 102 
    [ 5.000,  6.250) = 32 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 26 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.359 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.363 ms/op
     p(95.0000) =      2.556 ms/op
     p(99.0000) =      4.049 ms/op
     p(99.9000) =     12.960 ms/op
     p(99.9900) =     13.412 ms/op
     p(99.9990) =     13.435 ms/op
     p(99.9999) =     13.435 ms/op
    p(100.0000) =     13.435 ms/op


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
# Warmup Iteration   1: 4.732 ±(99.9%) 0.156 ms/op
Iteration   1: 3.536 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   1.184 ms/op
                 listUser·p0.50:   3.506 ms/op
                 listUser·p0.90:   4.186 ms/op
                 listUser·p0.95:   4.579 ms/op
                 listUser·p0.99:   6.061 ms/op
                 listUser·p0.999:  19.491 ms/op
                 listUser·p0.9999: 19.857 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9173
  mean =      3.536 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 463 
    [ 2.500,  3.750) = 5764 
    [ 3.750,  5.000) = 2633 
    [ 5.000,  6.250) = 231 
    [ 6.250,  7.500) = 42 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.184 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.186 ms/op
     p(95.0000) =      4.579 ms/op
     p(99.0000) =      6.061 ms/op
     p(99.9000) =     19.491 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.654          ops/ms
ClientSimple.existUser                       thrpt         12.784          ops/ms
ClientSimple.getUser                         thrpt         13.668          ops/ms
ClientSimple.listUser                        thrpt          8.398          ops/ms
ClientSimple.createUser                       avgt          2.187           ms/op
ClientSimple.existUser                        avgt          1.789           ms/op
ClientSimple.getUser                          avgt          2.118           ms/op
ClientSimple.listUser                         avgt          3.501           ms/op
ClientSimple.createUser                     sample  14374   2.220 ± 0.020   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.489           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.097           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.822           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.202           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.714           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.002           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.009           ms/op
ClientSimple.existUser                      sample  17835   1.804 ± 0.044   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.339           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.577           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.154           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.400           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.188           ms/op
ClientSimple.existUser:existUser·p0.999     sample         40.698           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         41.327           ms/op
ClientSimple.existUser:existUser·p1.00      sample         41.943           ms/op
ClientSimple.getUser                        sample  17050   1.879 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.359           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.745           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.363           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.556           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.049           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.960           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.412           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.435           ms/op
ClientSimple.listUser                       sample   9173   3.536 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.184           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.506           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.186           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.579           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.061           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.491           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.857           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.857           ms/op

Benchmark result is saved to 1722082663111.json
