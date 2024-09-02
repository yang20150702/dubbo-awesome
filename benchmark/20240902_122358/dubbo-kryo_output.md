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
# Warmup Iteration   1: 1.823 ops/ms
Iteration   1: 7.167 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.167 ops/ms


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
# Warmup Iteration   1: 5.511 ops/ms
Iteration   1: 11.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.232 ops/ms


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
# Warmup Iteration   1: 5.485 ops/ms
Iteration   1: 14.239 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.239 ops/ms


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
# Warmup Iteration   1: 5.368 ops/ms
Iteration   1: 8.850 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.850 ops/ms


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
# Warmup Iteration   1: 3.773 ±(99.9%) 0.072 ms/op
Iteration   1: 2.416 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.416 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.055 ms/op
Iteration   1: 1.974 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.974 ms/op


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
# Warmup Iteration   1: 3.342 ±(99.9%) 0.098 ms/op
Iteration   1: 2.154 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.154 ms/op


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
# Warmup Iteration   1: 4.168 ±(99.9%) 0.081 ms/op
Iteration   1: 3.059 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.059 ms/op


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
# Warmup Iteration   1: 3.382 ±(99.9%) 0.090 ms/op
Iteration   1: 2.350 ±(99.9%) 0.043 ms/op
                 createUser·p0.00:   0.415 ms/op
                 createUser·p0.50:   2.195 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   3.142 ms/op
                 createUser·p0.99:   5.374 ms/op
                 createUser·p0.999:  29.110 ms/op
                 createUser·p0.9999: 32.160 ms/op
                 createUser·p1.00:   32.244 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13655
  mean =      2.350 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10110 
    [ 2.500,  5.000) = 3322 
    [ 5.000,  7.500) = 126 
    [ 7.500, 10.000) = 2 
    [10.000, 12.500) = 63 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 3 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.415 ms/op
     p(50.0000) =      2.195 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      3.142 ms/op
     p(99.0000) =      5.374 ms/op
     p(99.9000) =     29.110 ms/op
     p(99.9900) =     32.160 ms/op
     p(99.9990) =     32.244 ms/op
     p(99.9999) =     32.244 ms/op
    p(100.0000) =     32.244 ms/op


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
# Warmup Iteration   1: 3.220 ±(99.9%) 0.082 ms/op
Iteration   1: 1.730 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.451 ms/op
                 existUser·p0.50:   1.452 ms/op
                 existUser·p0.90:   2.387 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   3.428 ms/op
                 existUser·p0.999:  24.642 ms/op
                 existUser·p0.9999: 25.470 ms/op
                 existUser·p1.00:   25.526 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18531
  mean =      1.730 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17222 
    [ 2.500,  5.000) = 1170 
    [ 5.000,  7.500) = 43 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 9 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.451 ms/op
     p(50.0000) =      1.452 ms/op
     p(90.0000) =      2.387 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      3.428 ms/op
     p(99.9000) =     24.642 ms/op
     p(99.9900) =     25.470 ms/op
     p(99.9990) =     25.526 ms/op
     p(99.9999) =     25.526 ms/op
    p(100.0000) =     25.526 ms/op


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
# Warmup Iteration   1: 3.136 ±(99.9%) 0.082 ms/op
Iteration   1: 1.741 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   0.647 ms/op
                 getUser·p0.50:   1.675 ms/op
                 getUser·p0.90:   1.993 ms/op
                 getUser·p0.95:   2.159 ms/op
                 getUser·p0.99:   2.703 ms/op
                 getUser·p0.999:  12.222 ms/op
                 getUser·p0.9999: 12.763 ms/op
                 getUser·p1.00:   12.763 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 18368
  mean =      1.741 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 95 
    [ 1.250,  2.500) = 17957 
    [ 2.500,  3.750) = 262 
    [ 3.750,  5.000) = 9 
    [ 5.000,  6.250) = 9 
    [ 6.250,  7.500) = 4 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 26 
    [12.500, 13.750) = 6 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.647 ms/op
     p(50.0000) =      1.675 ms/op
     p(90.0000) =      1.993 ms/op
     p(95.0000) =      2.159 ms/op
     p(99.0000) =      2.703 ms/op
     p(99.9000) =     12.222 ms/op
     p(99.9900) =     12.763 ms/op
     p(99.9990) =     12.763 ms/op
     p(99.9999) =     12.763 ms/op
    p(100.0000) =     12.763 ms/op


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
# Warmup Iteration   1: 4.579 ±(99.9%) 0.173 ms/op
Iteration   1: 3.770 ±(99.9%) 0.043 ms/op
                 listUser·p0.00:   1.023 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.612 ms/op
                 listUser·p0.99:   7.938 ms/op
                 listUser·p0.999:  19.239 ms/op
                 listUser·p0.9999: 19.956 ms/op
                 listUser·p1.00:   19.956 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8482
  mean =      3.770 ±(99.9%) 0.043 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 5 
    [ 1.250,  2.500) = 334 
    [ 2.500,  3.750) = 4063 
    [ 3.750,  5.000) = 3819 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 53 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 8 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 3 
    [17.500, 18.750) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.023 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.612 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     19.239 ms/op
     p(99.9900) =     19.956 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     19.956 ms/op
    p(100.0000) =     19.956 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.167          ops/ms
ClientSimple.existUser                       thrpt         11.232          ops/ms
ClientSimple.getUser                         thrpt         14.239          ops/ms
ClientSimple.listUser                        thrpt          8.850          ops/ms
ClientSimple.createUser                       avgt          2.416           ms/op
ClientSimple.existUser                        avgt          1.974           ms/op
ClientSimple.getUser                          avgt          2.154           ms/op
ClientSimple.listUser                         avgt          3.059           ms/op
ClientSimple.createUser                     sample  13655   2.350 ± 0.043   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.415           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.195           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.142           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.374           ms/op
ClientSimple.createUser:createUser·p0.999   sample         29.110           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         32.160           ms/op
ClientSimple.createUser:createUser·p1.00    sample         32.244           ms/op
ClientSimple.existUser                      sample  18531   1.730 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.451           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.452           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.387           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.626           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.428           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.642           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         25.470           ms/op
ClientSimple.existUser:existUser·p1.00      sample         25.526           ms/op
ClientSimple.getUser                        sample  18368   1.741 ± 0.013   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.647           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.675           ms/op
ClientSimple.getUser:getUser·p0.90          sample          1.993           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.159           ms/op
ClientSimple.getUser:getUser·p0.99          sample          2.703           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.222           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.763           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.763           ms/op
ClientSimple.listUser                       sample   8482   3.770 ± 0.043   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.023           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.731           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.612           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.938           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.239           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.956           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.956           ms/op

Benchmark result is saved to 1725279571441.json
