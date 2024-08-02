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
# Warmup Iteration   1: 1.606 ops/ms
Iteration   1: 6.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.880 ops/ms


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
# Warmup Iteration   1: 5.754 ops/ms
Iteration   1: 11.925 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.925 ops/ms


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
# Warmup Iteration   1: 6.086 ops/ms
Iteration   1: 12.655 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.655 ops/ms


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
# Warmup Iteration   1: 5.298 ops/ms
Iteration   1: 9.273 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.273 ops/ms


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
# Warmup Iteration   1: 3.695 ±(99.9%) 0.057 ms/op
Iteration   1: 2.091 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.091 ms/op


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
# Warmup Iteration   1: 3.490 ±(99.9%) 0.047 ms/op
Iteration   1: 1.876 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.876 ms/op


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
# Warmup Iteration   1: 3.124 ±(99.9%) 0.065 ms/op
Iteration   1: 1.905 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.905 ms/op


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
# Warmup Iteration   1: 6.029 ±(99.9%) 0.142 ms/op
Iteration   1: 3.520 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.520 ms/op


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
# Warmup Iteration   1: 4.160 ±(99.9%) 0.121 ms/op
Iteration   1: 2.206 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.908 ms/op
                 createUser·p0.50:   1.909 ms/op
                 createUser·p0.90:   2.773 ms/op
                 createUser·p0.95:   3.129 ms/op
                 createUser·p0.99:   7.702 ms/op
                 createUser·p0.999:  17.318 ms/op
                 createUser·p0.9999: 17.552 ms/op
                 createUser·p1.00:   17.596 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14489
  mean =      2.206 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 68 
    [ 1.250,  2.500) = 11764 
    [ 2.500,  3.750) = 2247 
    [ 3.750,  5.000) = 138 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 44 
    [16.250, 17.500) = 36 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.908 ms/op
     p(50.0000) =      1.909 ms/op
     p(90.0000) =      2.773 ms/op
     p(95.0000) =      3.129 ms/op
     p(99.0000) =      7.702 ms/op
     p(99.9000) =     17.318 ms/op
     p(99.9900) =     17.552 ms/op
     p(99.9990) =     17.596 ms/op
     p(99.9999) =     17.596 ms/op
    p(100.0000) =     17.596 ms/op


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
# Warmup Iteration   1: 3.043 ±(99.9%) 0.070 ms/op
Iteration   1: 2.095 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.556 ms/op
                 existUser·p0.50:   2.105 ms/op
                 existUser·p0.90:   2.580 ms/op
                 existUser·p0.95:   2.748 ms/op
                 existUser·p0.99:   3.141 ms/op
                 existUser·p0.999:  13.976 ms/op
                 existUser·p0.9999: 14.709 ms/op
                 existUser·p1.00:   14.778 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15311
  mean =      2.095 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 360 
    [ 1.250,  2.500) = 12818 
    [ 2.500,  3.750) = 2069 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.556 ms/op
     p(50.0000) =      2.105 ms/op
     p(90.0000) =      2.580 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      3.141 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     14.709 ms/op
     p(99.9990) =     14.778 ms/op
     p(99.9999) =     14.778 ms/op
    p(100.0000) =     14.778 ms/op


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
# Warmup Iteration   1: 3.255 ±(99.9%) 0.080 ms/op
Iteration   1: 2.044 ±(99.9%) 0.037 ms/op
                 getUser·p0.00:   0.554 ms/op
                 getUser·p0.50:   1.980 ms/op
                 getUser·p0.90:   2.478 ms/op
                 getUser·p0.95:   2.642 ms/op
                 getUser·p0.99:   3.825 ms/op
                 getUser·p0.999:  23.298 ms/op
                 getUser·p0.9999: 24.137 ms/op
                 getUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15650
  mean =      2.044 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14253 
    [ 2.500,  5.000) = 1276 
    [ 5.000,  7.500) = 57 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.554 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.478 ms/op
     p(95.0000) =      2.642 ms/op
     p(99.0000) =      3.825 ms/op
     p(99.9000) =     23.298 ms/op
     p(99.9900) =     24.137 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 4.172 ±(99.9%) 0.120 ms/op
Iteration   1: 3.642 ±(99.9%) 0.047 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.448 ms/op
                 listUser·p0.95:   4.751 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  21.825 ms/op
                 listUser·p0.9999: 23.527 ms/op
                 listUser·p1.00:   23.527 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8787
  mean =      3.642 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 544 
    [ 2.500,  5.000) = 7965 
    [ 5.000,  7.500) = 245 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.448 ms/op
     p(95.0000) =      4.751 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     21.825 ms/op
     p(99.9900) =     23.527 ms/op
     p(99.9990) =     23.527 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.880          ops/ms
ClientSimple.existUser                       thrpt         11.925          ops/ms
ClientSimple.getUser                         thrpt         12.655          ops/ms
ClientSimple.listUser                        thrpt          9.273          ops/ms
ClientSimple.createUser                       avgt          2.091           ms/op
ClientSimple.existUser                        avgt          1.876           ms/op
ClientSimple.getUser                          avgt          1.905           ms/op
ClientSimple.listUser                         avgt          3.520           ms/op
ClientSimple.createUser                     sample  14489   2.206 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.908           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.909           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.773           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.129           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.702           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.318           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.552           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.596           ms/op
ClientSimple.existUser                      sample  15311   2.095 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.556           ms/op
ClientSimple.existUser:existUser·p0.50      sample          2.105           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.580           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.748           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.141           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.976           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.709           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.778           ms/op
ClientSimple.getUser                        sample  15650   2.044 ± 0.037   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.554           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.980           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.478           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.642           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.825           ms/op
ClientSimple.getUser:getUser·p0.999         sample         23.298           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         24.137           ms/op
ClientSimple.getUser:getUser·p1.00          sample         24.248           ms/op
ClientSimple.listUser                       sample   8787   3.642 ± 0.047   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.163           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.448           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.751           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.627           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.825           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.527           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.527           ms/op

Benchmark result is saved to 1722579305961.json
