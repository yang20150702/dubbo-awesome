# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.934 ops/ms
Iteration   1: 7.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.141 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.722 ops/ms
Iteration   1: 13.569 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.569 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 6.586 ops/ms
Iteration   1: 14.173 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.173 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.464 ops/ms
Iteration   1: 9.015 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.015 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.696 ±(99.9%) 0.068 ms/op
Iteration   1: 2.324 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.324 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.144 ±(99.9%) 0.058 ms/op
Iteration   1: 2.000 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.000 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.241 ±(99.9%) 0.052 ms/op
Iteration   1: 2.129 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.129 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.460 ±(99.9%) 0.091 ms/op
Iteration   1: 2.989 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.989 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 3.398 ±(99.9%) 0.087 ms/op
Iteration   1: 2.003 ±(99.9%) 0.032 ms/op
                 createUser·p0.00:   0.373 ms/op
                 createUser·p0.50:   1.772 ms/op
                 createUser·p0.90:   2.523 ms/op
                 createUser·p0.95:   2.851 ms/op
                 createUser·p0.99:   6.308 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 17.662 ms/op
                 createUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15964
  mean =      2.003 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 673 
    [ 1.250,  2.500) = 13632 
    [ 2.500,  3.750) = 1275 
    [ 3.750,  5.000) = 154 
    [ 5.000,  6.250) = 66 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 17 
    [10.000, 11.250) = 27 
    [11.250, 12.500) = 49 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 19 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 21 
    [17.500, 18.750) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.373 ms/op
     p(50.0000) =      1.772 ms/op
     p(90.0000) =      2.523 ms/op
     p(95.0000) =      2.851 ms/op
     p(99.0000) =      6.308 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     17.662 ms/op
     p(99.9990) =     17.662 ms/op
     p(99.9999) =     17.662 ms/op
    p(100.0000) =     17.662 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.908 ±(99.9%) 0.071 ms/op
Iteration   1: 1.813 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.421 ms/op
                 existUser·p0.50:   1.778 ms/op
                 existUser·p0.90:   2.359 ms/op
                 existUser·p0.95:   2.478 ms/op
                 existUser·p0.99:   3.875 ms/op
                 existUser·p0.999:  15.125 ms/op
                 existUser·p0.9999: 15.457 ms/op
                 existUser·p1.00:   15.532 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17638
  mean =      1.813 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2721 
    [ 1.250,  2.500) = 14124 
    [ 2.500,  3.750) = 609 
    [ 3.750,  5.000) = 108 
    [ 5.000,  6.250) = 12 
    [ 6.250,  7.500) = 32 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 13 
    [15.000, 16.250) = 19 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      1.778 ms/op
     p(90.0000) =      2.359 ms/op
     p(95.0000) =      2.478 ms/op
     p(99.0000) =      3.875 ms/op
     p(99.9000) =     15.125 ms/op
     p(99.9900) =     15.457 ms/op
     p(99.9990) =     15.532 ms/op
     p(99.9999) =     15.532 ms/op
    p(100.0000) =     15.532 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.343 ±(99.9%) 0.094 ms/op
Iteration   1: 2.201 ±(99.9%) 0.042 ms/op
                 getUser·p0.00:   0.336 ms/op
                 getUser·p0.50:   2.109 ms/op
                 getUser·p0.90:   2.679 ms/op
                 getUser·p0.95:   2.875 ms/op
                 getUser·p0.99:   3.681 ms/op
                 getUser·p0.999:  29.131 ms/op
                 getUser·p0.9999: 29.899 ms/op
                 getUser·p1.00:   30.147 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14725
  mean =      2.201 ±(99.9%) 0.042 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11907 
    [ 2.500,  5.000) = 2753 
    [ 5.000,  7.500) = 1 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      2.109 ms/op
     p(90.0000) =      2.679 ms/op
     p(95.0000) =      2.875 ms/op
     p(99.0000) =      3.681 ms/op
     p(99.9000) =     29.131 ms/op
     p(99.9900) =     29.899 ms/op
     p(99.9990) =     30.147 ms/op
     p(99.9999) =     30.147 ms/op
    p(100.0000) =     30.147 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.568 ±(99.9%) 0.142 ms/op
Iteration   1: 3.653 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   1.100 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.465 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   6.189 ms/op
                 listUser·p0.999:  7.729 ms/op
                 listUser·p0.9999: 12.190 ms/op
                 listUser·p1.00:   12.190 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8750
  mean =      3.653 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2 
    [ 1.250,  2.500) = 520 
    [ 2.500,  3.750) = 4248 
    [ 3.750,  5.000) = 3698 
    [ 5.000,  6.250) = 196 
    [ 6.250,  7.500) = 68 
    [ 7.500,  8.750) = 17 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.674 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.653 ms/op
     p(99.0000) =      6.189 ms/op
     p(99.9000) =      7.729 ms/op
     p(99.9900) =     12.190 ms/op
     p(99.9990) =     12.190 ms/op
     p(99.9999) =     12.190 ms/op
    p(100.0000) =     12.190 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.141          ops/ms
ClientSimple.existUser                       thrpt         13.569          ops/ms
ClientSimple.getUser                         thrpt         14.173          ops/ms
ClientSimple.listUser                        thrpt          9.015          ops/ms
ClientSimple.createUser                       avgt          2.324           ms/op
ClientSimple.existUser                        avgt          2.000           ms/op
ClientSimple.getUser                          avgt          2.129           ms/op
ClientSimple.listUser                         avgt          2.989           ms/op
ClientSimple.createUser                     sample  15964   2.003 ± 0.032   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.373           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.772           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.523           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.851           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.308           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.433           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         17.662           ms/op
ClientSimple.createUser:createUser·p1.00    sample         17.662           ms/op
ClientSimple.existUser                      sample  17638   1.813 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.421           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.778           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.359           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.478           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.875           ms/op
ClientSimple.existUser:existUser·p0.999     sample         15.125           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         15.457           ms/op
ClientSimple.existUser:existUser·p1.00      sample         15.532           ms/op
ClientSimple.getUser                        sample  14725   2.201 ± 0.042   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.336           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.109           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.679           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.875           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.681           ms/op
ClientSimple.getUser:getUser·p0.999         sample         29.131           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         29.899           ms/op
ClientSimple.getUser:getUser·p1.00          sample         30.147           ms/op
ClientSimple.listUser                       sample   8750   3.653 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.100           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.674           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.465           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.653           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.189           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.729           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         12.190           ms/op
ClientSimple.listUser:listUser·p1.00        sample         12.190           ms/op

Benchmark result is saved to 1717308772872.json
