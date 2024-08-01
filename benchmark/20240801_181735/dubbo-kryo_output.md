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
# Warmup Iteration   1: 1.782 ops/ms
Iteration   1: 7.212 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.212 ops/ms


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
# Warmup Iteration   1: 5.162 ops/ms
Iteration   1: 11.196 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.196 ops/ms


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
# Warmup Iteration   1: 4.762 ops/ms
Iteration   1: 10.772 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.772 ops/ms


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
# Warmup Iteration   1: 4.126 ops/ms
Iteration   1: 8.883 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.883 ops/ms


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
# Warmup Iteration   1: 4.504 ±(99.9%) 0.088 ms/op
Iteration   1: 2.179 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.179 ms/op


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
# Warmup Iteration   1: 3.527 ±(99.9%) 0.068 ms/op
Iteration   1: 2.027 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.027 ms/op


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.072 ms/op
Iteration   1: 2.160 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.160 ms/op


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
# Warmup Iteration   1: 4.602 ±(99.9%) 0.117 ms/op
Iteration   1: 3.308 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.308 ms/op


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
# Warmup Iteration   1: 3.390 ±(99.9%) 0.095 ms/op
Iteration   1: 2.124 ±(99.9%) 0.046 ms/op
                 createUser·p0.00:   0.336 ms/op
                 createUser·p0.50:   1.874 ms/op
                 createUser·p0.90:   2.572 ms/op
                 createUser·p0.95:   2.993 ms/op
                 createUser·p0.99:   7.504 ms/op
                 createUser·p0.999:  34.587 ms/op
                 createUser·p0.9999: 35.193 ms/op
                 createUser·p1.00:   35.193 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15246
  mean =      2.124 ±(99.9%) 0.046 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13506 
    [ 2.500,  5.000) = 1502 
    [ 5.000,  7.500) = 85 
    [ 7.500, 10.000) = 57 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 11 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.572 ms/op
     p(95.0000) =      2.993 ms/op
     p(99.0000) =      7.504 ms/op
     p(99.9000) =     34.587 ms/op
     p(99.9900) =     35.193 ms/op
     p(99.9990) =     35.193 ms/op
     p(99.9999) =     35.193 ms/op
    p(100.0000) =     35.193 ms/op


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
# Warmup Iteration   1: 3.131 ±(99.9%) 0.082 ms/op
Iteration   1: 1.772 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   0.437 ms/op
                 existUser·p0.50:   1.661 ms/op
                 existUser·p0.90:   2.179 ms/op
                 existUser·p0.95:   2.388 ms/op
                 existUser·p0.99:   2.962 ms/op
                 existUser·p0.999:  10.386 ms/op
                 existUser·p0.9999: 11.452 ms/op
                 existUser·p1.00:   11.452 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18074
  mean =      1.772 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 211 
    [ 1.250,  2.500) = 17260 
    [ 2.500,  3.750) = 519 
    [ 3.750,  5.000) = 19 
    [ 5.000,  6.250) = 31 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.437 ms/op
     p(50.0000) =      1.661 ms/op
     p(90.0000) =      2.179 ms/op
     p(95.0000) =      2.388 ms/op
     p(99.0000) =      2.962 ms/op
     p(99.9000) =     10.386 ms/op
     p(99.9900) =     11.452 ms/op
     p(99.9990) =     11.452 ms/op
     p(99.9999) =     11.452 ms/op
    p(100.0000) =     11.452 ms/op


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
# Warmup Iteration   1: 3.624 ±(99.9%) 0.098 ms/op
Iteration   1: 2.331 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   0.805 ms/op
                 getUser·p0.50:   2.253 ms/op
                 getUser·p0.90:   2.916 ms/op
                 getUser·p0.95:   3.080 ms/op
                 getUser·p0.99:   4.153 ms/op
                 getUser·p0.999:  12.291 ms/op
                 getUser·p0.9999: 13.233 ms/op
                 getUser·p1.00:   13.566 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13834
  mean =      2.331 ±(99.9%) 0.020 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 69 
    [ 1.250,  2.500) = 9354 
    [ 2.500,  3.750) = 4218 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 52 
    [ 6.250,  7.500) = 1 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.805 ms/op
     p(50.0000) =      2.253 ms/op
     p(90.0000) =      2.916 ms/op
     p(95.0000) =      3.080 ms/op
     p(99.0000) =      4.153 ms/op
     p(99.9000) =     12.291 ms/op
     p(99.9900) =     13.233 ms/op
     p(99.9990) =     13.566 ms/op
     p(99.9999) =     13.566 ms/op
    p(100.0000) =     13.566 ms/op


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
# Warmup Iteration   1: 4.892 ±(99.9%) 0.166 ms/op
Iteration   1: 3.669 ±(99.9%) 0.085 ms/op
                 listUser·p0.00:   0.611 ms/op
                 listUser·p0.50:   3.211 ms/op
                 listUser·p0.90:   4.923 ms/op
                 listUser·p0.95:   5.308 ms/op
                 listUser·p0.99:   8.389 ms/op
                 listUser·p0.999:  37.965 ms/op
                 listUser·p0.9999: 38.535 ms/op
                 listUser·p1.00:   38.535 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8706
  mean =      3.669 ±(99.9%) 0.085 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 631 
    [ 2.500,  5.000) = 7302 
    [ 5.000,  7.500) = 677 
    [ 7.500, 10.000) = 16 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.923 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      8.389 ms/op
     p(99.9000) =     37.965 ms/op
     p(99.9900) =     38.535 ms/op
     p(99.9990) =     38.535 ms/op
     p(99.9999) =     38.535 ms/op
    p(100.0000) =     38.535 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.212          ops/ms
ClientSimple.existUser                       thrpt         11.196          ops/ms
ClientSimple.getUser                         thrpt         10.772          ops/ms
ClientSimple.listUser                        thrpt          8.883          ops/ms
ClientSimple.createUser                       avgt          2.179           ms/op
ClientSimple.existUser                        avgt          2.027           ms/op
ClientSimple.getUser                          avgt          2.160           ms/op
ClientSimple.listUser                         avgt          3.308           ms/op
ClientSimple.createUser                     sample  15246   2.124 ± 0.046   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.336           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.874           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.572           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.993           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.504           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.587           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         35.193           ms/op
ClientSimple.createUser:createUser·p1.00    sample         35.193           ms/op
ClientSimple.existUser                      sample  18074   1.772 ± 0.013   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.437           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.661           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.179           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.388           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.962           ms/op
ClientSimple.existUser:existUser·p0.999     sample         10.386           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.452           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.452           ms/op
ClientSimple.getUser                        sample  13834   2.331 ± 0.020   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.805           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.253           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.916           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.080           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.153           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.291           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.233           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.566           ms/op
ClientSimple.listUser                       sample   8706   3.669 ± 0.085   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.611           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.211           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.923           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.308           ms/op
ClientSimple.listUser:listUser·p0.99        sample          8.389           ms/op
ClientSimple.listUser:listUser·p0.999       sample         37.965           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         38.535           ms/op
ClientSimple.listUser:listUser·p1.00        sample         38.535           ms/op

Benchmark result is saved to 1722535946217.json
