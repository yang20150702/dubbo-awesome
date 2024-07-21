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
# Warmup Iteration   1: 2.174 ops/ms
Iteration   1: 8.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.200 ops/ms


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
# Warmup Iteration   1: 7.121 ops/ms
Iteration   1: 13.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.870 ops/ms


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
# Warmup Iteration   1: 5.904 ops/ms
Iteration   1: 13.293 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.293 ops/ms


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
# Warmup Iteration   1: 5.687 ops/ms
Iteration   1: 8.357 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.357 ops/ms


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
# Warmup Iteration   1: 3.697 ±(99.9%) 0.069 ms/op
Iteration   1: 2.063 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.063 ms/op


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
# Warmup Iteration   1: 3.064 ±(99.9%) 0.051 ms/op
Iteration   1: 1.825 ±(99.9%) 0.034 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.825 ms/op


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
# Warmup Iteration   1: 3.407 ±(99.9%) 0.053 ms/op
Iteration   1: 1.935 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.935 ms/op


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
# Warmup Iteration   1: 4.523 ±(99.9%) 0.084 ms/op
Iteration   1: 3.798 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.798 ms/op


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
# Warmup Iteration   1: 3.643 ±(99.9%) 0.088 ms/op
Iteration   1: 2.541 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   2.470 ms/op
                 createUser·p0.90:   3.084 ms/op
                 createUser·p0.95:   3.277 ms/op
                 createUser·p0.99:   4.163 ms/op
                 createUser·p0.999:  12.129 ms/op
                 createUser·p0.9999: 13.548 ms/op
                 createUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 12720
  mean =      2.541 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 58 
    [ 1.250,  2.500) = 6710 
    [ 2.500,  3.750) = 5672 
    [ 3.750,  5.000) = 183 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 2 
    [11.250, 12.500) = 62 
    [12.500, 13.750) = 3 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      2.470 ms/op
     p(90.0000) =      3.084 ms/op
     p(95.0000) =      3.277 ms/op
     p(99.0000) =      4.163 ms/op
     p(99.9000) =     12.129 ms/op
     p(99.9900) =     13.548 ms/op
     p(99.9990) =     13.615 ms/op
     p(99.9999) =     13.615 ms/op
    p(100.0000) =     13.615 ms/op


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
# Warmup Iteration   1: 3.068 ±(99.9%) 0.067 ms/op
Iteration   1: 2.119 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.587 ms/op
                 existUser·p0.50:   2.040 ms/op
                 existUser·p0.90:   2.531 ms/op
                 existUser·p0.95:   2.728 ms/op
                 existUser·p0.99:   5.177 ms/op
                 existUser·p0.999:  12.534 ms/op
                 existUser·p0.9999: 12.771 ms/op
                 existUser·p1.00:   12.796 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15083
  mean =      2.119 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 94 
    [ 1.250,  2.500) = 13297 
    [ 2.500,  3.750) = 1471 
    [ 3.750,  5.000) = 60 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 62 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.587 ms/op
     p(50.0000) =      2.040 ms/op
     p(90.0000) =      2.531 ms/op
     p(95.0000) =      2.728 ms/op
     p(99.0000) =      5.177 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     12.771 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.421 ±(99.9%) 0.079 ms/op
Iteration   1: 2.492 ±(99.9%) 0.045 ms/op
                 getUser·p0.00:   0.258 ms/op
                 getUser·p0.50:   2.445 ms/op
                 getUser·p0.90:   3.170 ms/op
                 getUser·p0.95:   3.531 ms/op
                 getUser·p0.99:   8.897 ms/op
                 getUser·p0.999:  23.396 ms/op
                 getUser·p0.9999: 23.551 ms/op
                 getUser·p1.00:   23.560 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 12826
  mean =      2.492 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7065 
    [ 2.500,  5.000) = 5492 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 137 
    [10.000, 12.500) = 51 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.258 ms/op
     p(50.0000) =      2.445 ms/op
     p(90.0000) =      3.170 ms/op
     p(95.0000) =      3.531 ms/op
     p(99.0000) =      8.897 ms/op
     p(99.9000) =     23.396 ms/op
     p(99.9900) =     23.551 ms/op
     p(99.9990) =     23.560 ms/op
     p(99.9999) =     23.560 ms/op
    p(100.0000) =     23.560 ms/op


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
# Warmup Iteration   1: 4.988 ±(99.9%) 0.160 ms/op
Iteration   1: 3.387 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   1.025 ms/op
                 listUser·p0.50:   3.043 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.578 ms/op
                 listUser·p0.99:   5.795 ms/op
                 listUser·p0.999:  16.466 ms/op
                 listUser·p0.9999: 16.531 ms/op
                 listUser·p1.00:   16.531 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9462
  mean =      3.387 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 4 
    [ 1.250,  2.500) = 132 
    [ 2.500,  3.750) = 6510 
    [ 3.750,  5.000) = 2581 
    [ 5.000,  6.250) = 156 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.025 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.578 ms/op
     p(99.0000) =      5.795 ms/op
     p(99.9000) =     16.466 ms/op
     p(99.9900) =     16.531 ms/op
     p(99.9990) =     16.531 ms/op
     p(99.9999) =     16.531 ms/op
    p(100.0000) =     16.531 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.200          ops/ms
ClientSimple.existUser                       thrpt         13.870          ops/ms
ClientSimple.getUser                         thrpt         13.293          ops/ms
ClientSimple.listUser                        thrpt          8.357          ops/ms
ClientSimple.createUser                       avgt          2.063           ms/op
ClientSimple.existUser                        avgt          1.825           ms/op
ClientSimple.getUser                          avgt          1.935           ms/op
ClientSimple.listUser                         avgt          3.798           ms/op
ClientSimple.createUser                     sample  12720   2.541 ± 0.025   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.640           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.470           ms/op
ClientSimple.createUser:createUser·p0.90    sample          3.084           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.277           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.163           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.129           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         13.548           ms/op
ClientSimple.createUser:createUser·p1.00    sample         13.615           ms/op
ClientSimple.existUser                      sample  15083   2.119 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.587           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.040           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.531           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.728           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.177           ms/op
ClientSimple.existUser:existUser·p0.999     sample         12.534           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.771           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.796           ms/op
ClientSimple.getUser                        sample  12826   2.492 ± 0.045   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.258           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.445           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.170           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.531           ms/op
ClientSimple.getUser:getUser·p0.99          sample          8.897           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.396           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.551           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.560           ms/op
ClientSimple.listUser                       sample   9462   3.387 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.025           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.043           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.578           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.795           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.466           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.531           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.531           ms/op

Benchmark result is saved to 1721522781390.json
