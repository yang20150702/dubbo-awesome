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
# Warmup Iteration   1: 0.785 ops/ms
Iteration   1: 5.416 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.416 ops/ms


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
# Warmup Iteration   1: 6.158 ops/ms
Iteration   1: 13.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.628 ops/ms


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
# Warmup Iteration   1: 5.555 ops/ms
Iteration   1: 12.034 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.034 ops/ms


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
# Warmup Iteration   1: 3.937 ops/ms
Iteration   1: 8.548 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.548 ops/ms


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
# Warmup Iteration   1: 4.422 ±(99.9%) 0.088 ms/op
Iteration   1: 2.048 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.048 ms/op


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
# Warmup Iteration   1: 3.471 ±(99.9%) 0.063 ms/op
Iteration   1: 2.224 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.224 ms/op


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
# Warmup Iteration   1: 3.144 ±(99.9%) 0.060 ms/op
Iteration   1: 1.918 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.918 ms/op


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
# Warmup Iteration   1: 4.454 ±(99.9%) 0.099 ms/op
Iteration   1: 3.887 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.887 ms/op


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
# Warmup Iteration   1: 3.942 ±(99.9%) 0.183 ms/op
Iteration   1: 2.301 ±(99.9%) 0.028 ms/op
                 createUser·p0.00:   0.525 ms/op
                 createUser·p0.50:   2.134 ms/op
                 createUser·p0.90:   2.916 ms/op
                 createUser·p0.95:   3.207 ms/op
                 createUser·p0.99:   7.733 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 12.478 ms/op
                 createUser·p1.00:   12.485 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14015
  mean =      2.301 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 305 
    [ 1.250,  2.500) = 9529 
    [ 2.500,  3.750) = 3748 
    [ 3.750,  5.000) = 202 
    [ 5.000,  6.250) = 30 
    [ 6.250,  7.500) = 51 
    [ 7.500,  8.750) = 70 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.525 ms/op
     p(50.0000) =      2.134 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.207 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     11.567 ms/op
     p(99.9900) =     12.478 ms/op
     p(99.9990) =     12.485 ms/op
     p(99.9999) =     12.485 ms/op
    p(100.0000) =     12.485 ms/op


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
# Warmup Iteration   1: 3.111 ±(99.9%) 0.100 ms/op
Iteration   1: 1.857 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   1.702 ms/op
                 existUser·p0.90:   2.261 ms/op
                 existUser·p0.95:   2.458 ms/op
                 existUser·p0.99:   3.236 ms/op
                 existUser·p0.999:  11.796 ms/op
                 existUser·p0.9999: 12.077 ms/op
                 existUser·p1.00:   12.124 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17216
  mean =      1.857 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 49 
    [ 1.250,  2.500) = 16446 
    [ 2.500,  3.750) = 568 
    [ 3.750,  5.000) = 85 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.788 ms/op
     p(50.0000) =      1.702 ms/op
     p(90.0000) =      2.261 ms/op
     p(95.0000) =      2.458 ms/op
     p(99.0000) =      3.236 ms/op
     p(99.9000) =     11.796 ms/op
     p(99.9900) =     12.077 ms/op
     p(99.9990) =     12.124 ms/op
     p(99.9999) =     12.124 ms/op
    p(100.0000) =     12.124 ms/op


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
# Warmup Iteration   1: 3.242 ±(99.9%) 0.088 ms/op
Iteration   1: 2.103 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.755 ms/op
                 getUser·p0.50:   2.013 ms/op
                 getUser·p0.90:   2.664 ms/op
                 getUser·p0.95:   2.837 ms/op
                 getUser·p0.99:   3.681 ms/op
                 getUser·p0.999:  11.108 ms/op
                 getUser·p0.9999: 12.295 ms/op
                 getUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15265
  mean =      2.103 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 77 
    [ 1.250,  2.500) = 12446 
    [ 2.500,  3.750) = 2616 
    [ 3.750,  5.000) = 64 
    [ 5.000,  6.250) = 29 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 23 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.755 ms/op
     p(50.0000) =      2.013 ms/op
     p(90.0000) =      2.664 ms/op
     p(95.0000) =      2.837 ms/op
     p(99.0000) =      3.681 ms/op
     p(99.9000) =     11.108 ms/op
     p(99.9900) =     12.295 ms/op
     p(99.9990) =     12.796 ms/op
     p(99.9999) =     12.796 ms/op
    p(100.0000) =     12.796 ms/op


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.140 ms/op
Iteration   1: 3.575 ±(99.9%) 0.060 ms/op
                 listUser·p0.00:   0.623 ms/op
                 listUser·p0.50:   3.437 ms/op
                 listUser·p0.90:   4.309 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.897 ms/op
                 listUser·p0.999:  23.462 ms/op
                 listUser·p0.9999: 23.626 ms/op
                 listUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8955
  mean =      3.575 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 627 
    [ 2.500,  5.000) = 7899 
    [ 5.000,  7.500) = 286 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.897 ms/op
     p(99.9000) =     23.462 ms/op
     p(99.9900) =     23.626 ms/op
     p(99.9990) =     23.626 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.416          ops/ms
ClientSimple.existUser                       thrpt         13.628          ops/ms
ClientSimple.getUser                         thrpt         12.034          ops/ms
ClientSimple.listUser                        thrpt          8.548          ops/ms
ClientSimple.createUser                       avgt          2.048           ms/op
ClientSimple.existUser                        avgt          2.224           ms/op
ClientSimple.getUser                          avgt          1.918           ms/op
ClientSimple.listUser                         avgt          3.887           ms/op
ClientSimple.createUser                     sample  14015   2.301 ± 0.028   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.525           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.134           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.916           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.207           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.733           ms/op
ClientSimple.createUser:createUser·p0.999   sample         11.567           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         12.478           ms/op
ClientSimple.createUser:createUser·p1.00    sample         12.485           ms/op
ClientSimple.existUser                      sample  17216   1.857 ± 0.018   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.788           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.702           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.261           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.458           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.236           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.796           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.077           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.124           ms/op
ClientSimple.getUser                        sample  15265   2.103 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.755           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.013           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.664           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.837           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.681           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.108           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.295           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.796           ms/op
ClientSimple.listUser                       sample   8955   3.575 ± 0.060   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.623           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.437           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.897           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.462           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.626           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.626           ms/op

Benchmark result is saved to 1721781819948.json
