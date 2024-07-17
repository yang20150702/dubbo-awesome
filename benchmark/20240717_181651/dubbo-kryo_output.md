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
# Warmup Iteration   1: 1.969 ops/ms
Iteration   1: 6.435 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.435 ops/ms


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
# Warmup Iteration   1: 6.165 ops/ms
Iteration   1: 12.615 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.615 ops/ms


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
# Warmup Iteration   1: 5.207 ops/ms
Iteration   1: 12.494 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.494 ops/ms


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
# Warmup Iteration   1: 4.797 ops/ms
Iteration   1: 8.671 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.671 ops/ms


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
# Warmup Iteration   1: 3.797 ±(99.9%) 0.068 ms/op
Iteration   1: 2.350 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.350 ms/op


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
# Warmup Iteration   1: 3.161 ±(99.9%) 0.049 ms/op
Iteration   1: 1.955 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.955 ms/op


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
# Warmup Iteration   1: 3.470 ±(99.9%) 0.062 ms/op
Iteration   1: 1.937 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.937 ms/op


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
# Warmup Iteration   1: 4.528 ±(99.9%) 0.114 ms/op
Iteration   1: 3.288 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.288 ms/op


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
# Warmup Iteration   1: 3.480 ±(99.9%) 0.086 ms/op
Iteration   1: 2.177 ±(99.9%) 0.036 ms/op
                 createUser·p0.00:   0.655 ms/op
                 createUser·p0.50:   1.874 ms/op
                 createUser·p0.90:   2.613 ms/op
                 createUser·p0.95:   3.018 ms/op
                 createUser·p0.99:   9.704 ms/op
                 createUser·p0.999:  17.957 ms/op
                 createUser·p0.9999: 18.090 ms/op
                 createUser·p1.00:   18.121 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14671
  mean =      2.177 ±(99.9%) 0.036 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 198 
    [ 1.250,  2.500) = 12427 
    [ 2.500,  3.750) = 1562 
    [ 3.750,  5.000) = 190 
    [ 5.000,  6.250) = 97 
    [ 6.250,  7.500) = 5 
    [ 7.500,  8.750) = 32 
    [ 8.750, 10.000) = 21 
    [10.000, 11.250) = 39 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 31 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.655 ms/op
     p(50.0000) =      1.874 ms/op
     p(90.0000) =      2.613 ms/op
     p(95.0000) =      3.018 ms/op
     p(99.0000) =      9.704 ms/op
     p(99.9000) =     17.957 ms/op
     p(99.9900) =     18.090 ms/op
     p(99.9990) =     18.121 ms/op
     p(99.9999) =     18.121 ms/op
    p(100.0000) =     18.121 ms/op


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
# Warmup Iteration   1: 3.361 ±(99.9%) 0.090 ms/op
Iteration   1: 1.853 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.567 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.470 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   4.214 ms/op
                 existUser·p0.999:  13.551 ms/op
                 existUser·p0.9999: 14.697 ms/op
                 existUser·p1.00:   14.746 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17459
  mean =      1.853 ±(99.9%) 0.019 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1034 
    [ 1.250,  2.500) = 14809 
    [ 2.500,  3.750) = 1413 
    [ 3.750,  5.000) = 148 
    [ 5.000,  6.250) = 11 
    [ 6.250,  7.500) = 6 
    [ 7.500,  8.750) = 7 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 19 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.567 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.470 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.214 ms/op
     p(99.9000) =     13.551 ms/op
     p(99.9900) =     14.697 ms/op
     p(99.9990) =     14.746 ms/op
     p(99.9999) =     14.746 ms/op
    p(100.0000) =     14.746 ms/op


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
# Warmup Iteration   1: 3.301 ±(99.9%) 0.077 ms/op
Iteration   1: 2.144 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.721 ms/op
                 getUser·p0.50:   1.999 ms/op
                 getUser·p0.90:   2.780 ms/op
                 getUser·p0.95:   2.998 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  20.546 ms/op
                 getUser·p0.9999: 20.940 ms/op
                 getUser·p1.00:   21.004 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14892
  mean =      2.144 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11897 
    [ 2.500,  5.000) = 2901 
    [ 5.000,  7.500) = 24 
    [ 7.500, 10.000) = 6 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.721 ms/op
     p(50.0000) =      1.999 ms/op
     p(90.0000) =      2.780 ms/op
     p(95.0000) =      2.998 ms/op
     p(99.0000) =      4.424 ms/op
     p(99.9000) =     20.546 ms/op
     p(99.9900) =     20.940 ms/op
     p(99.9990) =     21.004 ms/op
     p(99.9999) =     21.004 ms/op
    p(100.0000) =     21.004 ms/op


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
# Warmup Iteration   1: 4.745 ±(99.9%) 0.125 ms/op
Iteration   1: 3.600 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.807 ms/op
                 listUser·p0.50:   3.604 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.087 ms/op
                 listUser·p0.999:  13.592 ms/op
                 listUser·p0.9999: 14.696 ms/op
                 listUser·p1.00:   14.696 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8884
  mean =      3.600 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 13 
    [ 1.250,  2.500) = 988 
    [ 2.500,  3.750) = 4616 
    [ 3.750,  5.000) = 2902 
    [ 5.000,  6.250) = 218 
    [ 6.250,  7.500) = 63 
    [ 7.500,  8.750) = 9 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 35 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 7 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.807 ms/op
     p(50.0000) =      3.604 ms/op
     p(90.0000) =      4.391 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      7.087 ms/op
     p(99.9000) =     13.592 ms/op
     p(99.9900) =     14.696 ms/op
     p(99.9990) =     14.696 ms/op
     p(99.9999) =     14.696 ms/op
    p(100.0000) =     14.696 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.435          ops/ms
ClientSimple.existUser                       thrpt         12.615          ops/ms
ClientSimple.getUser                         thrpt         12.494          ops/ms
ClientSimple.listUser                        thrpt          8.671          ops/ms
ClientSimple.createUser                       avgt          2.350           ms/op
ClientSimple.existUser                        avgt          1.955           ms/op
ClientSimple.getUser                          avgt          1.937           ms/op
ClientSimple.listUser                         avgt          3.288           ms/op
ClientSimple.createUser                     sample  14671   2.177 ± 0.036   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.655           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.874           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.613           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.018           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.704           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.957           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.090           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.121           ms/op
ClientSimple.existUser                      sample  17459   1.853 ± 0.019   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.567           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.470           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.214           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.551           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         14.697           ms/op
ClientSimple.existUser:existUser·p1.00      sample         14.746           ms/op
ClientSimple.getUser                        sample  14892   2.144 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.721           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.999           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.780           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.998           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.424           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.546           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.940           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.004           ms/op
ClientSimple.listUser                       sample   8884   3.600 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.807           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.604           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.391           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.833           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.087           ms/op
ClientSimple.listUser:listUser·p0.999       sample         13.592           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         14.696           ms/op
ClientSimple.listUser:listUser·p1.00        sample         14.696           ms/op

Benchmark result is saved to 1721239965924.json
