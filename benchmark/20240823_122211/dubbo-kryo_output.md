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
# Warmup Iteration   1: 1.536 ops/ms
Iteration   1: 6.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.660 ops/ms


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
# Warmup Iteration   1: 5.275 ops/ms
Iteration   1: 9.268 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  9.268 ops/ms


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
# Warmup Iteration   1: 4.900 ops/ms
Iteration   1: 10.746 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.746 ops/ms


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
# Warmup Iteration   1: 4.128 ops/ms
Iteration   1: 7.608 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.608 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.057 ±(99.9%) 0.100 ms/op
Iteration   1: 2.599 ±(99.9%) 0.027 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.599 ms/op


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
# Warmup Iteration   1: 3.403 ±(99.9%) 0.061 ms/op
Iteration   1: 2.498 ±(99.9%) 0.036 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.498 ms/op


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
# Warmup Iteration   1: 3.837 ±(99.9%) 0.084 ms/op
Iteration   1: 2.042 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.042 ms/op


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
# Warmup Iteration   1: 4.876 ±(99.9%) 0.100 ms/op
Iteration   1: 3.260 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.260 ms/op


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
# Warmup Iteration   1: 3.642 ±(99.9%) 0.090 ms/op
Iteration   1: 2.331 ±(99.9%) 0.060 ms/op
                 createUser·p0.00:   0.668 ms/op
                 createUser·p0.50:   2.071 ms/op
                 createUser·p0.90:   2.638 ms/op
                 createUser·p0.95:   3.015 ms/op
                 createUser·p0.99:   11.059 ms/op
                 createUser·p0.999:  36.307 ms/op
                 createUser·p0.9999: 36.807 ms/op
                 createUser·p1.00:   36.831 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 13691
  mean =      2.331 ±(99.9%) 0.060 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11552 
    [ 2.500,  5.000) = 1848 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 64 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      2.071 ms/op
     p(90.0000) =      2.638 ms/op
     p(95.0000) =      3.015 ms/op
     p(99.0000) =     11.059 ms/op
     p(99.9000) =     36.307 ms/op
     p(99.9900) =     36.807 ms/op
     p(99.9990) =     36.831 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


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
# Warmup Iteration   1: 3.054 ±(99.9%) 0.067 ms/op
Iteration   1: 1.746 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   0.532 ms/op
                 existUser·p0.50:   1.645 ms/op
                 existUser·p0.90:   2.187 ms/op
                 existUser·p0.95:   2.322 ms/op
                 existUser·p0.99:   2.998 ms/op
                 existUser·p0.999:  14.724 ms/op
                 existUser·p0.9999: 15.682 ms/op
                 existUser·p1.00:   15.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18306
  mean =      1.746 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 681 
    [ 1.250,  2.500) = 17114 
    [ 2.500,  3.750) = 414 
    [ 3.750,  5.000) = 10 
    [ 5.000,  6.250) = 48 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 18 
    [15.000, 16.250) = 14 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.532 ms/op
     p(50.0000) =      1.645 ms/op
     p(90.0000) =      2.187 ms/op
     p(95.0000) =      2.322 ms/op
     p(99.0000) =      2.998 ms/op
     p(99.9000) =     14.724 ms/op
     p(99.9900) =     15.682 ms/op
     p(99.9990) =     15.696 ms/op
     p(99.9999) =     15.696 ms/op
    p(100.0000) =     15.696 ms/op


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
# Warmup Iteration   1: 3.512 ±(99.9%) 0.120 ms/op
Iteration   1: 2.060 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.696 ms/op
                 getUser·p0.50:   1.956 ms/op
                 getUser·p0.90:   2.712 ms/op
                 getUser·p0.95:   2.904 ms/op
                 getUser·p0.99:   3.330 ms/op
                 getUser·p0.999:  11.041 ms/op
                 getUser·p0.9999: 11.703 ms/op
                 getUser·p1.00:   11.911 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15526
  mean =      2.060 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 178 
    [ 1.250,  2.500) = 12559 
    [ 2.500,  3.750) = 2662 
    [ 3.750,  5.000) = 28 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 13 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.696 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.712 ms/op
     p(95.0000) =      2.904 ms/op
     p(99.0000) =      3.330 ms/op
     p(99.9000) =     11.041 ms/op
     p(99.9900) =     11.703 ms/op
     p(99.9990) =     11.911 ms/op
     p(99.9999) =     11.911 ms/op
    p(100.0000) =     11.911 ms/op


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
# Warmup Iteration   1: 5.926 ±(99.9%) 0.160 ms/op
Iteration   1: 3.583 ±(99.9%) 0.067 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.437 ms/op
                 listUser·p0.90:   4.325 ms/op
                 listUser·p0.95:   4.669 ms/op
                 listUser·p0.99:   12.916 ms/op
                 listUser·p0.999:  29.753 ms/op
                 listUser·p0.9999: 30.441 ms/op
                 listUser·p1.00:   30.441 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8945
  mean =      3.583 ±(99.9%) 0.067 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 636 
    [ 2.500,  5.000) = 8022 
    [ 5.000,  7.500) = 190 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 26 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.437 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =     12.916 ms/op
     p(99.9000) =     29.753 ms/op
     p(99.9900) =     30.441 ms/op
     p(99.9990) =     30.441 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.660          ops/ms
ClientSimple.existUser                       thrpt          9.268          ops/ms
ClientSimple.getUser                         thrpt         10.746          ops/ms
ClientSimple.listUser                        thrpt          7.608          ops/ms
ClientSimple.createUser                       avgt          2.599           ms/op
ClientSimple.existUser                        avgt          2.498           ms/op
ClientSimple.getUser                          avgt          2.042           ms/op
ClientSimple.listUser                         avgt          3.260           ms/op
ClientSimple.createUser                     sample  13691   2.331 ± 0.060   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.668           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.071           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.638           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.015           ms/op
ClientSimple.createUser:createUser·p0.99    sample         11.059           ms/op
ClientSimple.createUser:createUser·p0.999   sample         36.307           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         36.807           ms/op
ClientSimple.createUser:createUser·p1.00    sample         36.831           ms/op
ClientSimple.existUser                      sample  18306   1.746 ± 0.017   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.532           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.645           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.187           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.99      sample          2.998           ms/op
ClientSimple.existUser:existUser·p0.999     sample         14.724           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.682           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.696           ms/op
ClientSimple.getUser                        sample  15526   2.060 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.696           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.956           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.712           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.904           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.330           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.041           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         11.703           ms/op
ClientSimple.getUser:getUser·p1.00          sample         11.911           ms/op
ClientSimple.listUser                       sample   8945   3.583 ± 0.067   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.980           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.437           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.325           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.669           ms/op
ClientSimple.listUser:listUser·p0.99        sample         12.916           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.753           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         30.441           ms/op
ClientSimple.listUser:listUser·p1.00        sample         30.441           ms/op

Benchmark result is saved to 1724415469593.json
