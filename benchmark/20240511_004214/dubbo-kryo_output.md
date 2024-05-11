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
# Warmup Iteration   1: 1.020 ops/ms
Iteration   1: 5.762 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  5.762 ops/ms


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
# Warmup Iteration   1: 5.626 ops/ms
Iteration   1: 12.311 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.311 ops/ms


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
# Warmup Iteration   1: 5.237 ops/ms
Iteration   1: 12.321 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.321 ops/ms


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
# Warmup Iteration   1: 4.612 ops/ms
Iteration   1: 8.141 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.141 ops/ms


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
# Warmup Iteration   1: 4.065 ±(99.9%) 0.105 ms/op
Iteration   1: 2.440 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.440 ms/op


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
# Warmup Iteration   1: 3.270 ±(99.9%) 0.053 ms/op
Iteration   1: 2.024 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.024 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.062 ms/op
Iteration   1: 1.975 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.975 ms/op


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
# Warmup Iteration   1: 5.149 ±(99.9%) 0.121 ms/op
Iteration   1: 3.481 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.481 ms/op


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
# Warmup Iteration   1: 4.312 ±(99.9%) 0.124 ms/op
Iteration   1: 2.225 ±(99.9%) 0.037 ms/op
                 createUser·p0.00:   0.691 ms/op
                 createUser·p0.50:   1.972 ms/op
                 createUser·p0.90:   2.647 ms/op
                 createUser·p0.95:   3.200 ms/op
                 createUser·p0.99:   7.368 ms/op
                 createUser·p0.999:  20.152 ms/op
                 createUser·p0.9999: 23.852 ms/op
                 createUser·p1.00:   24.281 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14367
  mean =      2.225 ±(99.9%) 0.037 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12197 
    [ 2.500,  5.000) = 1824 
    [ 5.000,  7.500) = 204 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 31 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.691 ms/op
     p(50.0000) =      1.972 ms/op
     p(90.0000) =      2.647 ms/op
     p(95.0000) =      3.200 ms/op
     p(99.0000) =      7.368 ms/op
     p(99.9000) =     20.152 ms/op
     p(99.9900) =     23.852 ms/op
     p(99.9990) =     24.281 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 3.329 ±(99.9%) 0.085 ms/op
Iteration   1: 2.061 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.515 ms/op
                 existUser·p0.50:   1.798 ms/op
                 existUser·p0.90:   2.855 ms/op
                 existUser·p0.95:   3.125 ms/op
                 existUser·p0.99:   3.949 ms/op
                 existUser·p0.999:  20.611 ms/op
                 existUser·p0.9999: 20.862 ms/op
                 existUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15561
  mean =      2.061 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12708 
    [ 2.500,  5.000) = 2787 
    [ 5.000,  7.500) = 34 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.515 ms/op
     p(50.0000) =      1.798 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.125 ms/op
     p(99.0000) =      3.949 ms/op
     p(99.9000) =     20.611 ms/op
     p(99.9900) =     20.862 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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
# Warmup Iteration   1: 3.758 ±(99.9%) 0.128 ms/op
Iteration   1: 2.136 ±(99.9%) 0.031 ms/op
                 getUser·p0.00:   0.598 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.617 ms/op
                 getUser·p0.95:   2.798 ms/op
                 getUser·p0.99:   4.375 ms/op
                 getUser·p0.999:  22.709 ms/op
                 getUser·p0.9999: 23.495 ms/op
                 getUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14978
  mean =      2.136 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12522 
    [ 2.500,  5.000) = 2348 
    [ 5.000,  7.500) = 44 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.598 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.617 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =     22.709 ms/op
     p(99.9900) =     23.495 ms/op
     p(99.9990) =     23.658 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


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
# Warmup Iteration   1: 4.439 ±(99.9%) 0.119 ms/op
Iteration   1: 3.890 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   5.784 ms/op
                 listUser·p0.999:  8.176 ms/op
                 listUser·p0.9999: 8.200 ms/op
                 listUser·p1.00:   8.200 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8228
  mean =      3.890 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 1 
    [1.000, 1.500) = 21 
    [1.500, 2.000) = 64 
    [2.000, 2.500) = 125 
    [2.500, 3.000) = 941 
    [3.000, 3.500) = 958 
    [3.500, 4.000) = 2404 
    [4.000, 4.500) = 2429 
    [4.500, 5.000) = 904 
    [5.000, 5.500) = 210 
    [5.500, 6.000) = 115 
    [6.000, 6.500) = 12 
    [6.500, 7.000) = 17 
    [7.000, 7.500) = 5 
    [7.500, 8.000) = 1 
    [8.000, 8.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.686 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      5.784 ms/op
     p(99.9000) =      8.176 ms/op
     p(99.9900) =      8.200 ms/op
     p(99.9990) =      8.200 ms/op
     p(99.9999) =      8.200 ms/op
    p(100.0000) =      8.200 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          5.762          ops/ms
ClientSimple.existUser                       thrpt         12.311          ops/ms
ClientSimple.getUser                         thrpt         12.321          ops/ms
ClientSimple.listUser                        thrpt          8.141          ops/ms
ClientSimple.createUser                       avgt          2.440           ms/op
ClientSimple.existUser                        avgt          2.024           ms/op
ClientSimple.getUser                          avgt          1.975           ms/op
ClientSimple.listUser                         avgt          3.481           ms/op
ClientSimple.createUser                     sample  14367   2.225 ± 0.037   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.691           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.972           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.647           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.200           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.368           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.152           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.852           ms/op
ClientSimple.createUser:createUser·p1.00    sample         24.281           ms/op
ClientSimple.existUser                      sample  15561   2.061 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.515           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.798           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.855           ms/op
ClientSimple.existUser:existUser·p0.95      sample          3.125           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.949           ms/op
ClientSimple.existUser:existUser·p0.999     sample         20.611           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         20.862           ms/op
ClientSimple.existUser:existUser·p1.00      sample         20.972           ms/op
ClientSimple.getUser                        sample  14978   2.136 ± 0.031   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.598           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.617           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.798           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.375           ms/op
ClientSimple.getUser:getUser·p0.999         sample         22.709           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         23.495           ms/op
ClientSimple.getUser:getUser·p1.00          sample         23.658           ms/op
ClientSimple.listUser                       sample   8228   3.890 ± 0.027   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.890           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.686           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.784           ms/op
ClientSimple.listUser:listUser·p0.999       sample          8.176           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          8.200           ms/op
ClientSimple.listUser:listUser·p1.00        sample          8.200           ms/op

Benchmark result is saved to 1715387890249.json
