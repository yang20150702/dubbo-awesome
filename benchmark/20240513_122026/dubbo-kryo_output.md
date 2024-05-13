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
# Warmup Iteration   1: 1.914 ops/ms
Iteration   1: 7.587 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.587 ops/ms


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
# Warmup Iteration   1: 7.001 ops/ms
Iteration   1: 12.858 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.858 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.959 ops/ms
Iteration   1: 13.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.150 ops/ms


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
# Warmup Iteration   1: 5.687 ops/ms
Iteration   1: 8.005 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.005 ops/ms


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
# Warmup Iteration   1: 3.742 ±(99.9%) 0.066 ms/op
Iteration   1: 2.359 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.359 ms/op


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
# Warmup Iteration   1: 3.287 ±(99.9%) 0.059 ms/op
Iteration   1: 2.015 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.015 ms/op


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
# Warmup Iteration   1: 3.123 ±(99.9%) 0.048 ms/op
Iteration   1: 1.908 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.908 ms/op


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
# Warmup Iteration   1: 4.807 ±(99.9%) 0.114 ms/op
Iteration   1: 3.665 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.665 ms/op


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
# Warmup Iteration   1: 4.138 ±(99.9%) 0.128 ms/op
Iteration   1: 2.072 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.583 ms/op
                 createUser·p0.50:   1.907 ms/op
                 createUser·p0.90:   2.470 ms/op
                 createUser·p0.95:   2.781 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  12.747 ms/op
                 createUser·p0.9999: 14.444 ms/op
                 createUser·p1.00:   14.811 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15465
  mean =      2.072 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 143 
    [ 1.250,  2.500) = 13889 
    [ 2.500,  3.750) = 1085 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 111 
    [ 6.250,  7.500) = 18 
    [ 7.500,  8.750) = 23 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.583 ms/op
     p(50.0000) =      1.907 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.781 ms/op
     p(99.0000) =      5.644 ms/op
     p(99.9000) =     12.747 ms/op
     p(99.9900) =     14.444 ms/op
     p(99.9990) =     14.811 ms/op
     p(99.9999) =     14.811 ms/op
    p(100.0000) =     14.811 ms/op


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
# Warmup Iteration   1: 3.110 ±(99.9%) 0.084 ms/op
Iteration   1: 1.893 ±(99.9%) 0.034 ms/op
                 existUser·p0.00:   0.457 ms/op
                 existUser·p0.50:   1.753 ms/op
                 existUser·p0.90:   2.322 ms/op
                 existUser·p0.95:   2.490 ms/op
                 existUser·p0.99:   3.084 ms/op
                 existUser·p0.999:  31.661 ms/op
                 existUser·p0.9999: 34.271 ms/op
                 existUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16898
  mean =      1.893 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16132 
    [ 2.500,  5.000) = 679 
    [ 5.000,  7.500) = 4 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 36 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 1 
    [27.500, 30.000) = 5 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      1.753 ms/op
     p(90.0000) =      2.322 ms/op
     p(95.0000) =      2.490 ms/op
     p(99.0000) =      3.084 ms/op
     p(99.9000) =     31.661 ms/op
     p(99.9900) =     34.271 ms/op
     p(99.9990) =     34.406 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 3.280 ±(99.9%) 0.083 ms/op
Iteration   1: 2.246 ±(99.9%) 0.038 ms/op
                 getUser·p0.00:   0.673 ms/op
                 getUser·p0.50:   2.042 ms/op
                 getUser·p0.90:   2.941 ms/op
                 getUser·p0.95:   3.158 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  25.692 ms/op
                 getUser·p0.9999: 26.650 ms/op
                 getUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14233
  mean =      2.246 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11274 
    [ 2.500,  5.000) = 2819 
    [ 5.000,  7.500) = 76 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.673 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.941 ms/op
     p(95.0000) =      3.158 ms/op
     p(99.0000) =      4.989 ms/op
     p(99.9000) =     25.692 ms/op
     p(99.9900) =     26.650 ms/op
     p(99.9990) =     26.706 ms/op
     p(99.9999) =     26.706 ms/op
    p(100.0000) =     26.706 ms/op


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
# Warmup Iteration   1: 4.757 ±(99.9%) 0.158 ms/op
Iteration   1: 3.557 ±(99.9%) 0.030 ms/op
                 listUser·p0.00:   0.616 ms/op
                 listUser·p0.50:   3.580 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.866 ms/op
                 listUser·p0.99:   5.983 ms/op
                 listUser·p0.999:  7.946 ms/op
                 listUser·p0.9999: 8.733 ms/op
                 listUser·p1.00:   8.733 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9015
  mean =      3.557 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 2 
    [1.000, 1.500) = 10 
    [1.500, 2.000) = 94 
    [2.000, 2.500) = 801 
    [2.500, 3.000) = 1619 
    [3.000, 3.500) = 1697 
    [3.500, 4.000) = 2103 
    [4.000, 4.500) = 1713 
    [4.500, 5.000) = 668 
    [5.000, 5.500) = 98 
    [5.500, 6.000) = 123 
    [6.000, 6.500) = 32 
    [6.500, 7.000) = 8 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 39 
    [8.000, 8.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      3.580 ms/op
     p(90.0000) =      4.538 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      5.983 ms/op
     p(99.9000) =      7.946 ms/op
     p(99.9900) =      8.733 ms/op
     p(99.9990) =      8.733 ms/op
     p(99.9999) =      8.733 ms/op
    p(100.0000) =      8.733 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.587          ops/ms
ClientSimple.existUser                       thrpt         12.858          ops/ms
ClientSimple.getUser                         thrpt         13.150          ops/ms
ClientSimple.listUser                        thrpt          8.005          ops/ms
ClientSimple.createUser                       avgt          2.359           ms/op
ClientSimple.existUser                        avgt          2.015           ms/op
ClientSimple.getUser                          avgt          1.908           ms/op
ClientSimple.listUser                         avgt          3.665           ms/op
ClientSimple.createUser                     sample  15465   2.072 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.583           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.907           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.470           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.781           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.644           ms/op
ClientSimple.createUser:createUser·p0.999   sample         12.747           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         14.444           ms/op
ClientSimple.createUser:createUser·p1.00    sample         14.811           ms/op
ClientSimple.existUser                      sample  16898   1.893 ± 0.034   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.457           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.753           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.322           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.490           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.084           ms/op
ClientSimple.existUser:existUser·p0.999     sample         31.661           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         34.271           ms/op
ClientSimple.existUser:existUser·p1.00      sample         34.406           ms/op
ClientSimple.getUser                        sample  14233   2.246 ± 0.038   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.673           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.042           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.941           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.158           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.989           ms/op
ClientSimple.getUser:getUser·p0.999         sample         25.692           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         26.650           ms/op
ClientSimple.getUser:getUser·p1.00          sample         26.706           ms/op
ClientSimple.listUser                       sample   9015   3.557 ± 0.030   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.616           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.580           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.538           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.866           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.983           ms/op
ClientSimple.listUser:listUser·p0.999       sample          7.946           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.733           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.733           ms/op

Benchmark result is saved to 1715602567567.json
