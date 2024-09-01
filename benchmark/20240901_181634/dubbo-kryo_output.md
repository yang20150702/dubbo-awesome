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
# Warmup Iteration   1: 1.922 ops/ms
Iteration   1: 6.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.670 ops/ms


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
# Warmup Iteration   1: 5.487 ops/ms
Iteration   1: 12.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.525 ops/ms


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
# Warmup Iteration   1: 5.930 ops/ms
Iteration   1: 13.650 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  13.650 ops/ms


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
# Warmup Iteration   1: 3.936 ops/ms
Iteration   1: 8.563 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.563 ops/ms


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
# Warmup Iteration   1: 4.527 ±(99.9%) 0.090 ms/op
Iteration   1: 2.283 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.283 ms/op


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
# Warmup Iteration   1: 3.097 ±(99.9%) 0.047 ms/op
Iteration   1: 2.011 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.011 ms/op


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
# Warmup Iteration   1: 3.192 ±(99.9%) 0.048 ms/op
Iteration   1: 1.840 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.840 ms/op


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
# Warmup Iteration   1: 4.596 ±(99.9%) 0.094 ms/op
Iteration   1: 3.480 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.480 ms/op


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
# Warmup Iteration   1: 3.721 ±(99.9%) 0.090 ms/op
Iteration   1: 2.277 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   1.017 ms/op
                 createUser·p0.50:   2.089 ms/op
                 createUser·p0.90:   2.601 ms/op
                 createUser·p0.95:   2.748 ms/op
                 createUser·p0.99:   5.772 ms/op
                 createUser·p0.999:  27.032 ms/op
                 createUser·p0.9999: 30.644 ms/op
                 createUser·p1.00:   30.671 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14046
  mean =      2.277 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11889 
    [ 2.500,  5.000) = 2007 
    [ 5.000,  7.500) = 56 
    [ 7.500, 10.000) = 30 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 21 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.017 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.601 ms/op
     p(95.0000) =      2.748 ms/op
     p(99.0000) =      5.772 ms/op
     p(99.9000) =     27.032 ms/op
     p(99.9900) =     30.644 ms/op
     p(99.9990) =     30.671 ms/op
     p(99.9999) =     30.671 ms/op
    p(100.0000) =     30.671 ms/op


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
# Warmup Iteration   1: 3.095 ±(99.9%) 0.068 ms/op
Iteration   1: 1.789 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   1.577 ms/op
                 existUser·p0.90:   2.372 ms/op
                 existUser·p0.95:   2.568 ms/op
                 existUser·p0.99:   3.203 ms/op
                 existUser·p0.999:  21.729 ms/op
                 existUser·p0.9999: 22.500 ms/op
                 existUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17888
  mean =      1.789 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16714 
    [ 2.500,  5.000) = 1082 
    [ 5.000,  7.500) = 16 
    [ 7.500, 10.000) = 3 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 2 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      1.577 ms/op
     p(90.0000) =      2.372 ms/op
     p(95.0000) =      2.568 ms/op
     p(99.0000) =      3.203 ms/op
     p(99.9000) =     21.729 ms/op
     p(99.9900) =     22.500 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


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
# Warmup Iteration   1: 3.420 ±(99.9%) 0.086 ms/op
Iteration   1: 1.993 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.806 ms/op
                 getUser·p0.50:   1.876 ms/op
                 getUser·p0.90:   2.609 ms/op
                 getUser·p0.95:   2.789 ms/op
                 getUser·p0.99:   3.346 ms/op
                 getUser·p0.999:  11.649 ms/op
                 getUser·p0.9999: 12.689 ms/op
                 getUser·p1.00:   12.845 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16345
  mean =      1.993 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 136 
    [ 1.250,  2.500) = 13987 
    [ 2.500,  3.750) = 2119 
    [ 3.750,  5.000) = 37 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 12 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 15 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.806 ms/op
     p(50.0000) =      1.876 ms/op
     p(90.0000) =      2.609 ms/op
     p(95.0000) =      2.789 ms/op
     p(99.0000) =      3.346 ms/op
     p(99.9000) =     11.649 ms/op
     p(99.9900) =     12.689 ms/op
     p(99.9990) =     12.845 ms/op
     p(99.9999) =     12.845 ms/op
    p(100.0000) =     12.845 ms/op


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.131 ms/op
Iteration   1: 3.127 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   1.798 ms/op
                 listUser·p0.50:   2.855 ms/op
                 listUser·p0.90:   4.022 ms/op
                 listUser·p0.95:   4.260 ms/op
                 listUser·p0.99:   5.197 ms/op
                 listUser·p0.999:  16.796 ms/op
                 listUser·p0.9999: 16.940 ms/op
                 listUser·p1.00:   16.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10414
  mean =      3.127 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 0 
    [ 1.250,  2.500) = 557 
    [ 2.500,  3.750) = 8111 
    [ 3.750,  5.000) = 1624 
    [ 5.000,  6.250) = 87 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.798 ms/op
     p(50.0000) =      2.855 ms/op
     p(90.0000) =      4.022 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.197 ms/op
     p(99.9000) =     16.796 ms/op
     p(99.9900) =     16.940 ms/op
     p(99.9990) =     16.941 ms/op
     p(99.9999) =     16.941 ms/op
    p(100.0000) =     16.941 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.670          ops/ms
ClientSimple.existUser                       thrpt         12.525          ops/ms
ClientSimple.getUser                         thrpt         13.650          ops/ms
ClientSimple.listUser                        thrpt          8.563          ops/ms
ClientSimple.createUser                       avgt          2.283           ms/op
ClientSimple.existUser                        avgt          2.011           ms/op
ClientSimple.getUser                          avgt          1.840           ms/op
ClientSimple.listUser                         avgt          3.480           ms/op
ClientSimple.createUser                     sample  14046   2.277 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.017           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.089           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.601           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.748           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.772           ms/op
ClientSimple.createUser:createUser·p0.999   sample         27.032           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         30.644           ms/op
ClientSimple.createUser:createUser·p1.00    sample         30.671           ms/op
ClientSimple.existUser                      sample  17888   1.789 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.784           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.577           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.372           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.568           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.203           ms/op
ClientSimple.existUser:existUser·p0.999     sample         21.729           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         22.500           ms/op
ClientSimple.existUser:existUser·p1.00      sample         22.577           ms/op
ClientSimple.getUser                        sample  16345   1.993 ± 0.017   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.806           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.876           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.609           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.789           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.346           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.649           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         12.689           ms/op
ClientSimple.getUser:getUser·p1.00          sample         12.845           ms/op
ClientSimple.listUser                       sample  10414   3.127 ± 0.031   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.798           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.855           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.022           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.260           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.197           ms/op
ClientSimple.listUser:listUser·p0.999       sample         16.796           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         16.940           ms/op
ClientSimple.listUser:listUser·p1.00        sample         16.941           ms/op

Benchmark result is saved to 1725214342377.json
