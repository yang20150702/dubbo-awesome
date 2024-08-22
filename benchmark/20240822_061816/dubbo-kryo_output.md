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
# Warmup Iteration   1: 1.960 ops/ms
Iteration   1: 7.466 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.466 ops/ms


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
# Warmup Iteration   1: 5.445 ops/ms
Iteration   1: 12.657 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.657 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.929 ops/ms
Iteration   1: 13.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.360 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.663 ops/ms
Iteration   1: 8.502 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.502 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 4.646 ±(99.9%) 0.092 ms/op
Iteration   1: 1.991 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  1.991 ms/op


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
# Warmup Iteration   1: 3.527 ±(99.9%) 0.058 ms/op
Iteration   1: 1.816 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.816 ms/op


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
# Warmup Iteration   1: 3.346 ±(99.9%) 0.059 ms/op
Iteration   1: 2.135 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.135 ms/op


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
# Warmup Iteration   1: 4.234 ±(99.9%) 0.084 ms/op
Iteration   1: 3.306 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.306 ms/op


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
# Warmup Iteration   1: 3.317 ±(99.9%) 0.078 ms/op
Iteration   1: 2.074 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.702 ms/op
                 createUser·p0.50:   1.921 ms/op
                 createUser·p0.90:   2.556 ms/op
                 createUser·p0.95:   2.937 ms/op
                 createUser·p0.99:   5.636 ms/op
                 createUser·p0.999:  19.890 ms/op
                 createUser·p0.9999: 21.165 ms/op
                 createUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15473
  mean =      2.074 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13710 
    [ 2.500,  5.000) = 1587 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 38 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.702 ms/op
     p(50.0000) =      1.921 ms/op
     p(90.0000) =      2.556 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      5.636 ms/op
     p(99.9000) =     19.890 ms/op
     p(99.9900) =     21.165 ms/op
     p(99.9990) =     21.201 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 3.128 ±(99.9%) 0.072 ms/op
Iteration   1: 1.837 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.650 ms/op
                 existUser·p0.50:   1.718 ms/op
                 existUser·p0.90:   2.302 ms/op
                 existUser·p0.95:   2.507 ms/op
                 existUser·p0.99:   2.889 ms/op
                 existUser·p0.999:  11.889 ms/op
                 existUser·p0.9999: 12.002 ms/op
                 existUser·p1.00:   12.026 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17377
  mean =      1.837 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 200 
    [ 1.250,  2.500) = 16293 
    [ 2.500,  3.750) = 805 
    [ 3.750,  5.000) = 45 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 32 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.650 ms/op
     p(50.0000) =      1.718 ms/op
     p(90.0000) =      2.302 ms/op
     p(95.0000) =      2.507 ms/op
     p(99.0000) =      2.889 ms/op
     p(99.9000) =     11.889 ms/op
     p(99.9900) =     12.002 ms/op
     p(99.9990) =     12.026 ms/op
     p(99.9999) =     12.026 ms/op
    p(100.0000) =     12.026 ms/op


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
# Warmup Iteration   1: 3.293 ±(99.9%) 0.079 ms/op
Iteration   1: 1.922 ±(99.9%) 0.030 ms/op
                 getUser·p0.00:   0.408 ms/op
                 getUser·p0.50:   1.767 ms/op
                 getUser·p0.90:   2.425 ms/op
                 getUser·p0.95:   2.568 ms/op
                 getUser·p0.99:   3.556 ms/op
                 getUser·p0.999:  21.082 ms/op
                 getUser·p0.9999: 21.725 ms/op
                 getUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16634
  mean =      1.922 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15476 
    [ 2.500,  5.000) = 1044 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      1.767 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.556 ms/op
     p(99.9000) =     21.082 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.410 ±(99.9%) 0.132 ms/op
Iteration   1: 3.363 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   0.775 ms/op
                 listUser·p0.50:   3.265 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.649 ms/op
                 listUser·p0.99:   5.825 ms/op
                 listUser·p0.999:  12.501 ms/op
                 listUser·p0.9999: 14.877 ms/op
                 listUser·p1.00:   14.877 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9510
  mean =      3.363 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 10 
    [ 1.250,  2.500) = 854 
    [ 2.500,  3.750) = 5971 
    [ 3.750,  5.000) = 2401 
    [ 5.000,  6.250) = 196 
    [ 6.250,  7.500) = 49 
    [ 7.500,  8.750) = 11 
    [ 8.750, 10.000) = 5 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 10 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.775 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      4.202 ms/op
     p(95.0000) =      4.649 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     12.501 ms/op
     p(99.9900) =     14.877 ms/op
     p(99.9990) =     14.877 ms/op
     p(99.9999) =     14.877 ms/op
    p(100.0000) =     14.877 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.466          ops/ms
ClientSimple.existUser                       thrpt         12.657          ops/ms
ClientSimple.getUser                         thrpt         13.360          ops/ms
ClientSimple.listUser                        thrpt          8.502          ops/ms
ClientSimple.createUser                       avgt          1.991           ms/op
ClientSimple.existUser                        avgt          1.816           ms/op
ClientSimple.getUser                          avgt          2.135           ms/op
ClientSimple.listUser                         avgt          3.306           ms/op
ClientSimple.createUser                     sample  15473   2.074 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.702           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.921           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.556           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.636           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.890           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.165           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.201           ms/op
ClientSimple.existUser                      sample  17377   1.837 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.650           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.718           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.302           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.507           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.889           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.889           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         12.002           ms/op
ClientSimple.existUser:existUser·p1.00      sample         12.026           ms/op
ClientSimple.getUser                        sample  16634   1.922 ± 0.030   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.408           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.767           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.425           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.568           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.556           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.082           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.725           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.791           ms/op
ClientSimple.listUser                       sample   9510   3.363 ± 0.029   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.775           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.265           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.202           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.649           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.825           ms/op
ClientSimple.listUser:listUser·p0.999       sample         12.501           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.877           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.877           ms/op

Benchmark result is saved to 1724307230431.json
