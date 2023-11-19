# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.419 ops/ms
Iteration   1: 6.078 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.078 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 6.061 ops/ms
Iteration   1: 14.059 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  14.059 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.616 ops/ms
Iteration   1: 9.316 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  9.316 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.021 ops/ms
Iteration   1: 3.746 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.746 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.968 ±(99.9%) 0.078 ms/op
Iteration   1: 2.634 ±(99.9%) 0.055 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.634 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.358 ±(99.9%) 0.046 ms/op
Iteration   1: 1.805 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.805 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 4.337 ±(99.9%) 0.046 ms/op
Iteration   1: 2.825 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.825 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.173 ±(99.9%) 0.183 ms/op
Iteration   1: 7.652 ±(99.9%) 0.088 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.652 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.732 ±(99.9%) 0.091 ms/op
Iteration   1: 2.661 ±(99.9%) 0.033 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   2.535 ms/op
                 createUser·p0.90:   3.396 ms/op
                 createUser·p0.95:   3.822 ms/op
                 createUser·p0.99:   5.226 ms/op
                 createUser·p0.999:  16.450 ms/op
                 createUser·p0.9999: 16.649 ms/op
                 createUser·p1.00:   16.679 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 11999
  mean =      2.661 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 9 
    [ 1.250,  2.500) = 5696 
    [ 2.500,  3.750) = 5646 
    [ 3.750,  5.000) = 485 
    [ 5.000,  6.250) = 64 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 6 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 31 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      2.535 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      5.226 ms/op
     p(99.9000) =     16.450 ms/op
     p(99.9900) =     16.649 ms/op
     p(99.9990) =     16.679 ms/op
     p(99.9999) =     16.679 ms/op
    p(100.0000) =     16.679 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 2.971 ±(99.9%) 0.055 ms/op
Iteration   1: 1.933 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.467 ms/op
                 existUser·p0.50:   1.872 ms/op
                 existUser·p0.90:   2.425 ms/op
                 existUser·p0.95:   2.626 ms/op
                 existUser·p0.99:   4.487 ms/op
                 existUser·p0.999:  10.304 ms/op
                 existUser·p0.9999: 11.321 ms/op
                 existUser·p1.00:   11.633 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 16561
  mean =      1.933 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 767 
    [ 1.250,  2.500) = 14532 
    [ 2.500,  3.750) = 996 
    [ 3.750,  5.000) = 121 
    [ 5.000,  6.250) = 49 
    [ 6.250,  7.500) = 29 
    [ 7.500,  8.750) = 14 
    [ 8.750, 10.000) = 36 
    [10.000, 11.250) = 16 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      1.872 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.626 ms/op
     p(99.0000) =      4.487 ms/op
     p(99.9000) =     10.304 ms/op
     p(99.9900) =     11.321 ms/op
     p(99.9990) =     11.633 ms/op
     p(99.9999) =     11.633 ms/op
    p(100.0000) =     11.633 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 4.463 ±(99.9%) 0.124 ms/op
Iteration   1: 2.895 ±(99.9%) 0.063 ms/op
                 getUser·p0.00:   0.438 ms/op
                 getUser·p0.50:   2.671 ms/op
                 getUser·p0.90:   3.949 ms/op
                 getUser·p0.95:   4.276 ms/op
                 getUser·p0.99:   6.013 ms/op
                 getUser·p0.999:  36.173 ms/op
                 getUser·p0.9999: 37.911 ms/op
                 getUser·p1.00:   37.945 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 11050
  mean =      2.895 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4732 
    [ 2.500,  5.000) = 6072 
    [ 5.000,  7.500) = 205 
    [ 7.500, 10.000) = 8 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.438 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.949 ms/op
     p(95.0000) =      4.276 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     36.173 ms/op
     p(99.9900) =     37.911 ms/op
     p(99.9990) =     37.945 ms/op
     p(99.9999) =     37.945 ms/op
    p(100.0000) =     37.945 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 11.682 ±(99.9%) 0.457 ms/op
Iteration   1: 7.051 ±(99.9%) 0.109 ms/op
                 listUser·p0.00:   2.568 ms/op
                 listUser·p0.50:   6.758 ms/op
                 listUser·p0.90:   9.165 ms/op
                 listUser·p0.95:   10.309 ms/op
                 listUser·p0.99:   17.199 ms/op
                 listUser·p0.999:  24.281 ms/op
                 listUser·p0.9999: 25.494 ms/op
                 listUser·p1.00:   25.494 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 4555
  mean =      7.051 ±(99.9%) 0.109 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 517 
    [ 5.000,  7.500) = 2584 
    [ 7.500, 10.000) = 1187 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.568 ms/op
     p(50.0000) =      6.758 ms/op
     p(90.0000) =      9.165 ms/op
     p(95.0000) =     10.309 ms/op
     p(99.0000) =     17.199 ms/op
     p(99.9000) =     24.281 ms/op
     p(99.9900) =     25.494 ms/op
     p(99.9990) =     25.494 ms/op
     p(99.9999) =     25.494 ms/op
    p(100.0000) =     25.494 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.078          ops/ms
Client.existUser                       thrpt         14.059          ops/ms
Client.getUser                         thrpt          9.316          ops/ms
Client.listUser                        thrpt          3.746          ops/ms
Client.createUser                       avgt          2.634           ms/op
Client.existUser                        avgt          1.805           ms/op
Client.getUser                          avgt          2.825           ms/op
Client.listUser                         avgt          7.652           ms/op
Client.createUser                     sample  11999   2.661 ± 0.033   ms/op
Client.createUser:createUser·p0.00    sample          1.106           ms/op
Client.createUser:createUser·p0.50    sample          2.535           ms/op
Client.createUser:createUser·p0.90    sample          3.396           ms/op
Client.createUser:createUser·p0.95    sample          3.822           ms/op
Client.createUser:createUser·p0.99    sample          5.226           ms/op
Client.createUser:createUser·p0.999   sample         16.450           ms/op
Client.createUser:createUser·p0.9999  sample         16.649           ms/op
Client.createUser:createUser·p1.00    sample         16.679           ms/op
Client.existUser                      sample  16561   1.933 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.467           ms/op
Client.existUser:existUser·p0.50      sample          1.872           ms/op
Client.existUser:existUser·p0.90      sample          2.425           ms/op
Client.existUser:existUser·p0.95      sample          2.626           ms/op
Client.existUser:existUser·p0.99      sample          4.487           ms/op
Client.existUser:existUser·p0.999     sample         10.304           ms/op
Client.existUser:existUser·p0.9999    sample         11.321           ms/op
Client.existUser:existUser·p1.00      sample         11.633           ms/op
Client.getUser                        sample  11050   2.895 ± 0.063   ms/op
Client.getUser:getUser·p0.00          sample          0.438           ms/op
Client.getUser:getUser·p0.50          sample          2.671           ms/op
Client.getUser:getUser·p0.90          sample          3.949           ms/op
Client.getUser:getUser·p0.95          sample          4.276           ms/op
Client.getUser:getUser·p0.99          sample          6.013           ms/op
Client.getUser:getUser·p0.999         sample         36.173           ms/op
Client.getUser:getUser·p0.9999        sample         37.911           ms/op
Client.getUser:getUser·p1.00          sample         37.945           ms/op
Client.listUser                       sample   4555   7.051 ± 0.109   ms/op
Client.listUser:listUser·p0.00        sample          2.568           ms/op
Client.listUser:listUser·p0.50        sample          6.758           ms/op
Client.listUser:listUser·p0.90        sample          9.165           ms/op
Client.listUser:listUser·p0.95        sample         10.309           ms/op
Client.listUser:listUser·p0.99        sample         17.199           ms/op
Client.listUser:listUser·p0.999       sample         24.281           ms/op
Client.listUser:listUser·p0.9999      sample         25.494           ms/op
Client.listUser:listUser·p1.00        sample         25.494           ms/op
