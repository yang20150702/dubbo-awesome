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
# Warmup Iteration   1: 1.375 ops/ms
Iteration   1: 6.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.554 ops/ms


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
# Warmup Iteration   1: 7.361 ops/ms
Iteration   1: 13.317 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.317 ops/ms


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
# Warmup Iteration   1: 5.570 ops/ms
Iteration   1: 14.433 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.433 ops/ms


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
# Warmup Iteration   1: 5.010 ops/ms
Iteration   1: 8.939 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.939 ops/ms


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.070 ms/op
Iteration   1: 2.119 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.119 ms/op


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
# Warmup Iteration   1: 3.046 ±(99.9%) 0.048 ms/op
Iteration   1: 1.861 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.861 ms/op


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
# Warmup Iteration   1: 3.760 ±(99.9%) 0.078 ms/op
Iteration   1: 2.059 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.059 ms/op


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
# Warmup Iteration   1: 4.710 ±(99.9%) 0.094 ms/op
Iteration   1: 3.301 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.301 ms/op


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
# Warmup Iteration   1: 3.387 ±(99.9%) 0.081 ms/op
Iteration   1: 2.074 ±(99.9%) 0.047 ms/op
                 createUser·p0.00:   0.677 ms/op
                 createUser·p0.50:   1.860 ms/op
                 createUser·p0.90:   2.355 ms/op
                 createUser·p0.95:   2.650 ms/op
                 createUser·p0.99:   5.128 ms/op
                 createUser·p0.999:  34.144 ms/op
                 createUser·p0.9999: 38.242 ms/op
                 createUser·p1.00:   38.470 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15784
  mean =      2.074 ±(99.9%) 0.047 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14774 
    [ 2.500,  5.000) = 818 
    [ 5.000,  7.500) = 95 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 21 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.355 ms/op
     p(95.0000) =      2.650 ms/op
     p(99.0000) =      5.128 ms/op
     p(99.9000) =     34.144 ms/op
     p(99.9900) =     38.242 ms/op
     p(99.9990) =     38.470 ms/op
     p(99.9999) =     38.470 ms/op
    p(100.0000) =     38.470 ms/op


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
# Warmup Iteration   1: 3.175 ±(99.9%) 0.085 ms/op
Iteration   1: 1.987 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   0.744 ms/op
                 existUser·p0.50:   1.819 ms/op
                 existUser·p0.90:   2.703 ms/op
                 existUser·p0.95:   2.941 ms/op
                 existUser·p0.99:   4.874 ms/op
                 existUser·p0.999:  13.545 ms/op
                 existUser·p0.9999: 13.615 ms/op
                 existUser·p1.00:   13.615 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16295
  mean =      1.987 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 517 
    [ 1.250,  2.500) = 12981 
    [ 2.500,  3.750) = 2515 
    [ 3.750,  5.000) = 153 
    [ 5.000,  6.250) = 65 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 30 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.744 ms/op
     p(50.0000) =      1.819 ms/op
     p(90.0000) =      2.703 ms/op
     p(95.0000) =      2.941 ms/op
     p(99.0000) =      4.874 ms/op
     p(99.9000) =     13.545 ms/op
     p(99.9900) =     13.615 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.184 ±(99.9%) 0.072 ms/op
Iteration   1: 2.182 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.706 ms/op
                 getUser·p0.50:   2.171 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.744 ms/op
                 getUser·p0.99:   3.230 ms/op
                 getUser·p0.999:  12.431 ms/op
                 getUser·p0.9999: 12.700 ms/op
                 getUser·p1.00:   12.730 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14649
  mean =      2.182 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 103 
    [ 1.250,  2.500) = 11966 
    [ 2.500,  3.750) = 2470 
    [ 3.750,  5.000) = 78 
    [ 5.000,  6.250) = 0 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 20 
    [12.500, 13.750) = 12 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      2.171 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.230 ms/op
     p(99.9000) =     12.431 ms/op
     p(99.9900) =     12.700 ms/op
     p(99.9990) =     12.730 ms/op
     p(99.9999) =     12.730 ms/op
    p(100.0000) =     12.730 ms/op


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
# Warmup Iteration   1: 5.237 ±(99.9%) 0.162 ms/op
Iteration   1: 3.682 ±(99.9%) 0.062 ms/op
                 listUser·p0.00:   0.824 ms/op
                 listUser·p0.50:   3.555 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   4.817 ms/op
                 listUser·p0.99:   7.287 ms/op
                 listUser·p0.999:  23.396 ms/op
                 listUser·p0.9999: 26.411 ms/op
                 listUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8681
  mean =      3.682 ±(99.9%) 0.062 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 650 
    [ 2.500,  5.000) = 7667 
    [ 5.000,  7.500) = 291 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 14 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.824 ms/op
     p(50.0000) =      3.555 ms/op
     p(90.0000) =      4.301 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      7.287 ms/op
     p(99.9000) =     23.396 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.554          ops/ms
ClientSimple.existUser                       thrpt         13.317          ops/ms
ClientSimple.getUser                         thrpt         14.433          ops/ms
ClientSimple.listUser                        thrpt          8.939          ops/ms
ClientSimple.createUser                       avgt          2.119           ms/op
ClientSimple.existUser                        avgt          1.861           ms/op
ClientSimple.getUser                          avgt          2.059           ms/op
ClientSimple.listUser                         avgt          3.301           ms/op
ClientSimple.createUser                     sample  15784   2.074 ± 0.047   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.677           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.860           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.355           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.650           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.128           ms/op
ClientSimple.createUser:createUser·p0.999   sample         34.144           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         38.242           ms/op
ClientSimple.createUser:createUser·p1.00    sample         38.470           ms/op
ClientSimple.existUser                      sample  16295   1.987 ± 0.023   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.744           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.819           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.941           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.874           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.545           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         13.615           ms/op
ClientSimple.existUser:existUser·p1.00      sample         13.615           ms/op
ClientSimple.getUser                        sample  14649   2.182 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.706           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.171           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.744           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.230           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.431           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.700           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.730           ms/op
ClientSimple.listUser                       sample   8681   3.682 ± 0.062   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.824           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.555           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.301           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.817           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.287           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.396           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         26.411           ms/op
ClientSimple.listUser:listUser·p1.00        sample         26.411           ms/op

Benchmark result is saved to 1724546891258.json
