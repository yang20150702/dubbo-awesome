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
# Warmup Iteration   1: 1.886 ops/ms
Iteration   1: 6.424 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.424 ops/ms


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
# Warmup Iteration   1: 5.740 ops/ms
Iteration   1: 13.402 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.402 ops/ms


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
# Warmup Iteration   1: 6.229 ops/ms
Iteration   1: 14.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.224 ops/ms


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
# Warmup Iteration   1: 4.979 ops/ms
Iteration   1: 8.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.651 ops/ms


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
# Warmup Iteration   1: 3.782 ±(99.9%) 0.069 ms/op
Iteration   1: 2.009 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.009 ms/op


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
# Warmup Iteration   1: 3.117 ±(99.9%) 0.057 ms/op
Iteration   1: 1.904 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.904 ms/op


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
# Warmup Iteration   1: 3.279 ±(99.9%) 0.057 ms/op
Iteration   1: 2.057 ±(99.9%) 0.008 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.427 ±(99.9%) 0.095 ms/op
Iteration   1: 3.412 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.412 ms/op


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
# Warmup Iteration   1: 3.564 ±(99.9%) 0.095 ms/op
Iteration   1: 2.091 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   0.445 ms/op
                 createUser·p0.50:   1.948 ms/op
                 createUser·p0.90:   2.437 ms/op
                 createUser·p0.95:   2.693 ms/op
                 createUser·p0.99:   5.825 ms/op
                 createUser·p0.999:  20.707 ms/op
                 createUser·p0.9999: 27.180 ms/op
                 createUser·p1.00:   27.197 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15290
  mean =      2.091 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14077 
    [ 2.500,  5.000) = 935 
    [ 5.000,  7.500) = 148 
    [ 7.500, 10.000) = 34 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.445 ms/op
     p(50.0000) =      1.948 ms/op
     p(90.0000) =      2.437 ms/op
     p(95.0000) =      2.693 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     20.707 ms/op
     p(99.9900) =     27.180 ms/op
     p(99.9990) =     27.197 ms/op
     p(99.9999) =     27.197 ms/op
    p(100.0000) =     27.197 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.950 ±(99.9%) 0.065 ms/op
Iteration   1: 1.886 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.418 ms/op
                 existUser·p0.50:   1.788 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.392 ms/op
                 existUser·p0.99:   3.019 ms/op
                 existUser·p0.999:  19.104 ms/op
                 existUser·p0.9999: 19.857 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16983
  mean =      1.886 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 441 
    [ 1.250,  2.500) = 15992 
    [ 2.500,  3.750) = 447 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.418 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.392 ms/op
     p(99.0000) =      3.019 ms/op
     p(99.9000) =     19.104 ms/op
     p(99.9900) =     19.857 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 3.214 ±(99.9%) 0.075 ms/op
Iteration   1: 1.852 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   1.759 ms/op
                 getUser·p0.90:   2.118 ms/op
                 getUser·p0.95:   2.372 ms/op
                 getUser·p0.99:   2.941 ms/op
                 getUser·p0.999:  11.878 ms/op
                 getUser·p0.9999: 12.128 ms/op
                 getUser·p1.00:   12.141 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17363
  mean =      1.852 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 74 
    [ 1.250,  2.500) = 16765 
    [ 2.500,  3.750) = 425 
    [ 3.750,  5.000) = 1 
    [ 5.000,  6.250) = 34 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      1.759 ms/op
     p(90.0000) =      2.118 ms/op
     p(95.0000) =      2.372 ms/op
     p(99.0000) =      2.941 ms/op
     p(99.9000) =     11.878 ms/op
     p(99.9900) =     12.128 ms/op
     p(99.9990) =     12.141 ms/op
     p(99.9999) =     12.141 ms/op
    p(100.0000) =     12.141 ms/op


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
# Warmup Iteration   1: 4.548 ±(99.9%) 0.117 ms/op
Iteration   1: 3.010 ±(99.9%) 0.036 ms/op
                 listUser·p0.00:   0.973 ms/op
                 listUser·p0.50:   2.822 ms/op
                 listUser·p0.90:   3.662 ms/op
                 listUser·p0.95:   3.918 ms/op
                 listUser·p0.99:   4.932 ms/op
                 listUser·p0.999:  21.606 ms/op
                 listUser·p0.9999: 22.411 ms/op
                 listUser·p1.00:   22.413 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10629
  mean =      3.010 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 636 
    [ 2.500,  5.000) = 9897 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.973 ms/op
     p(50.0000) =      2.822 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.918 ms/op
     p(99.0000) =      4.932 ms/op
     p(99.9000) =     21.606 ms/op
     p(99.9900) =     22.411 ms/op
     p(99.9990) =     22.413 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.424          ops/ms
ClientSimple.existUser                       thrpt         13.402          ops/ms
ClientSimple.getUser                         thrpt         14.224          ops/ms
ClientSimple.listUser                        thrpt          8.651          ops/ms
ClientSimple.createUser                       avgt          2.009           ms/op
ClientSimple.existUser                        avgt          1.904           ms/op
ClientSimple.getUser                          avgt          2.057           ms/op
ClientSimple.listUser                         avgt          3.412           ms/op
ClientSimple.createUser                     sample  15290   2.091 ± 0.033   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.445           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.948           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.437           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.693           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.825           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.707           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         27.180           ms/op
ClientSimple.createUser:createUser·p1.00    sample         27.197           ms/op
ClientSimple.existUser                      sample  16983   1.886 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.418           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.788           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.208           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.392           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.019           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.104           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.857           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.857           ms/op
ClientSimple.getUser                        sample  17363   1.852 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.746           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.759           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.118           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.372           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.878           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.128           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.141           ms/op
ClientSimple.listUser                       sample  10629   3.010 ± 0.036   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.973           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.822           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.662           ms/op
ClientSimple.listUser:listUser·p0.95        sample          3.918           ms/op
ClientSimple.listUser:listUser·p0.99        sample          4.932           ms/op
ClientSimple.listUser:listUser·p0.999       sample         21.606           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         22.411           ms/op
ClientSimple.listUser:listUser·p1.00        sample         22.413           ms/op

Benchmark result is saved to 1721628823400.json
