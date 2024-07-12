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
# Warmup Iteration   1: 2.082 ops/ms
Iteration   1: 6.519 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.519 ops/ms


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
# Warmup Iteration   1: 4.973 ops/ms
Iteration   1: 12.092 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.092 ops/ms


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
# Warmup Iteration   1: 5.061 ops/ms
Iteration   1: 10.731 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  10.731 ops/ms


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
# Warmup Iteration   1: 4.828 ops/ms
Iteration   1: 8.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.558 ops/ms


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
# Warmup Iteration   1: 3.676 ±(99.9%) 0.068 ms/op
Iteration   1: 2.010 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.010 ms/op


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
# Warmup Iteration   1: 3.189 ±(99.9%) 0.060 ms/op
Iteration   1: 2.063 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.063 ms/op


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
# Warmup Iteration   1: 3.321 ±(99.9%) 0.061 ms/op
Iteration   1: 1.962 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.962 ms/op


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
# Warmup Iteration   1: 4.546 ±(99.9%) 0.085 ms/op
Iteration   1: 3.258 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.258 ms/op


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
# Warmup Iteration   1: 3.542 ±(99.9%) 0.091 ms/op
Iteration   1: 2.143 ±(99.9%) 0.041 ms/op
                 createUser·p0.00:   0.748 ms/op
                 createUser·p0.50:   1.946 ms/op
                 createUser·p0.90:   2.474 ms/op
                 createUser·p0.95:   3.007 ms/op
                 createUser·p0.99:   8.323 ms/op
                 createUser·p0.999:  24.805 ms/op
                 createUser·p0.9999: 28.967 ms/op
                 createUser·p1.00:   29.950 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14915
  mean =      2.143 ±(99.9%) 0.041 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13509 
    [ 2.500,  5.000) = 1153 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 109 
    [10.000, 12.500) = 7 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      1.946 ms/op
     p(90.0000) =      2.474 ms/op
     p(95.0000) =      3.007 ms/op
     p(99.0000) =      8.323 ms/op
     p(99.9000) =     24.805 ms/op
     p(99.9900) =     28.967 ms/op
     p(99.9990) =     29.950 ms/op
     p(99.9999) =     29.950 ms/op
    p(100.0000) =     29.950 ms/op


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
# Warmup Iteration   1: 3.014 ±(99.9%) 0.072 ms/op
Iteration   1: 2.155 ±(99.9%) 0.063 ms/op
                 existUser·p0.00:   0.403 ms/op
                 existUser·p0.50:   1.952 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.654 ms/op
                 existUser·p0.99:   4.422 ms/op
                 existUser·p0.999:  44.958 ms/op
                 existUser·p0.9999: 45.877 ms/op
                 existUser·p1.00:   45.941 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 14830
  mean =      2.155 ±(99.9%) 0.063 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 14721 
    [ 5.000, 10.000) = 7 
    [10.000, 15.000) = 31 
    [15.000, 20.000) = 4 
    [20.000, 25.000) = 3 
    [25.000, 30.000) = 35 
    [30.000, 35.000) = 3 
    [35.000, 40.000) = 1 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.403 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.654 ms/op
     p(99.0000) =      4.422 ms/op
     p(99.9000) =     44.958 ms/op
     p(99.9900) =     45.877 ms/op
     p(99.9990) =     45.941 ms/op
     p(99.9999) =     45.941 ms/op
    p(100.0000) =     45.941 ms/op


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
# Warmup Iteration   1: 3.365 ±(99.9%) 0.080 ms/op
Iteration   1: 2.065 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.470 ms/op
                 getUser·p0.50:   1.952 ms/op
                 getUser·p0.90:   2.425 ms/op
                 getUser·p0.95:   2.572 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  12.911 ms/op
                 getUser·p0.9999: 13.171 ms/op
                 getUser·p1.00:   13.189 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15490
  mean =      2.065 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 189 
    [ 1.250,  2.500) = 14177 
    [ 2.500,  3.750) = 880 
    [ 3.750,  5.000) = 75 
    [ 5.000,  6.250) = 82 
    [ 6.250,  7.500) = 23 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 41 
    [12.500, 13.750) = 23 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.470 ms/op
     p(50.0000) =      1.952 ms/op
     p(90.0000) =      2.425 ms/op
     p(95.0000) =      2.572 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     12.911 ms/op
     p(99.9900) =     13.171 ms/op
     p(99.9990) =     13.189 ms/op
     p(99.9999) =     13.189 ms/op
    p(100.0000) =     13.189 ms/op


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.127 ms/op
Iteration   1: 3.433 ±(99.9%) 0.034 ms/op
                 listUser·p0.00:   0.959 ms/op
                 listUser·p0.50:   3.424 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.710 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  10.797 ms/op
                 listUser·p0.9999: 10.895 ms/op
                 listUser·p1.00:   10.895 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9335
  mean =      3.433 ±(99.9%) 0.034 ms/op

  Histogram, ms/op:
    [ 0.000,  1.000) = 1 
    [ 1.000,  2.000) = 326 
    [ 2.000,  3.000) = 2906 
    [ 3.000,  4.000) = 3753 
    [ 4.000,  5.000) = 2025 
    [ 5.000,  6.000) = 177 
    [ 6.000,  7.000) = 68 
    [ 7.000,  8.000) = 46 
    [ 8.000,  9.000) = 1 
    [ 9.000, 10.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.959 ms/op
     p(50.0000) =      3.424 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.710 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     10.797 ms/op
     p(99.9900) =     10.895 ms/op
     p(99.9990) =     10.895 ms/op
     p(99.9999) =     10.895 ms/op
    p(100.0000) =     10.895 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.519          ops/ms
ClientSimple.existUser                       thrpt         12.092          ops/ms
ClientSimple.getUser                         thrpt         10.731          ops/ms
ClientSimple.listUser                        thrpt          8.558          ops/ms
ClientSimple.createUser                       avgt          2.010           ms/op
ClientSimple.existUser                        avgt          2.063           ms/op
ClientSimple.getUser                          avgt          1.962           ms/op
ClientSimple.listUser                         avgt          3.258           ms/op
ClientSimple.createUser                     sample  14915   2.143 ± 0.041   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.748           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.946           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.474           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.007           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.323           ms/op
ClientSimple.createUser:createUser·p0.999   sample         24.805           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         28.967           ms/op
ClientSimple.createUser:createUser·p1.00    sample         29.950           ms/op
ClientSimple.existUser                      sample  14830   2.155 ± 0.063   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.403           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.952           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.654           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.422           ms/op
ClientSimple.existUser:existUser·p0.999     sample         44.958           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         45.877           ms/op
ClientSimple.existUser:existUser·p1.00      sample         45.941           ms/op
ClientSimple.getUser                        sample  15490   2.065 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.470           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.952           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.425           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.572           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.530           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.911           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.171           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.189           ms/op
ClientSimple.listUser                       sample   9335   3.433 ± 0.034   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.959           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.424           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.415           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.710           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.922           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.797           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.895           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.895           ms/op

Benchmark result is saved to 1720807911337.json
