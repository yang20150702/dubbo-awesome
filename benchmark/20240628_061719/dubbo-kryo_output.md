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
# Warmup Iteration   1: 1.883 ops/ms
Iteration   1: 7.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.203 ops/ms


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
# Warmup Iteration   1: 6.056 ops/ms
Iteration   1: 13.301 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.301 ops/ms


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
# Warmup Iteration   1: 6.378 ops/ms
Iteration   1: 14.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.521 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.623 ops/ms
Iteration   1: 8.436 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.436 ops/ms


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
# Warmup Iteration   1: 4.640 ±(99.9%) 0.084 ms/op
Iteration   1: 2.241 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.241 ms/op


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
# Warmup Iteration   1: 3.448 ±(99.9%) 0.068 ms/op
Iteration   1: 1.953 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.953 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.089 ms/op
Iteration   1: 1.961 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.961 ms/op


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
# Warmup Iteration   1: 4.641 ±(99.9%) 0.094 ms/op
Iteration   1: 3.586 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.586 ms/op


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
# Warmup Iteration   1: 3.432 ±(99.9%) 0.093 ms/op
Iteration   1: 2.219 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.679 ms/op
                 createUser·p0.50:   1.982 ms/op
                 createUser·p0.90:   2.740 ms/op
                 createUser·p0.95:   2.974 ms/op
                 createUser·p0.99:   9.001 ms/op
                 createUser·p0.999:  20.760 ms/op
                 createUser·p0.9999: 21.692 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14463
  mean =      2.219 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11466 
    [ 2.500,  5.000) = 2763 
    [ 5.000,  7.500) = 73 
    [ 7.500, 10.000) = 44 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.679 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.740 ms/op
     p(95.0000) =      2.974 ms/op
     p(99.0000) =      9.001 ms/op
     p(99.9000) =     20.760 ms/op
     p(99.9900) =     21.692 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 3.468 ±(99.9%) 0.111 ms/op
Iteration   1: 1.921 ±(99.9%) 0.030 ms/op
                 existUser·p0.00:   0.666 ms/op
                 existUser·p0.50:   1.745 ms/op
                 existUser·p0.90:   2.286 ms/op
                 existUser·p0.95:   2.576 ms/op
                 existUser·p0.99:   4.119 ms/op
                 existUser·p0.999:  24.161 ms/op
                 existUser·p0.9999: 24.347 ms/op
                 existUser·p1.00:   24.347 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16649
  mean =      1.921 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15617 
    [ 2.500,  5.000) = 886 
    [ 5.000,  7.500) = 75 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 12 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.666 ms/op
     p(50.0000) =      1.745 ms/op
     p(90.0000) =      2.286 ms/op
     p(95.0000) =      2.576 ms/op
     p(99.0000) =      4.119 ms/op
     p(99.9000) =     24.161 ms/op
     p(99.9900) =     24.347 ms/op
     p(99.9990) =     24.347 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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
# Warmup Iteration   1: 3.529 ±(99.9%) 0.085 ms/op
Iteration   1: 2.176 ±(99.9%) 0.027 ms/op
                 getUser·p0.00:   0.676 ms/op
                 getUser·p0.50:   2.089 ms/op
                 getUser·p0.90:   2.593 ms/op
                 getUser·p0.95:   2.811 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  20.251 ms/op
                 getUser·p0.9999: 21.532 ms/op
                 getUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14753
  mean =      2.176 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12728 
    [ 2.500,  5.000) = 1893 
    [ 5.000,  7.500) = 93 
    [ 7.500, 10.000) = 5 
    [10.000, 12.500) = 2 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.676 ms/op
     p(50.0000) =      2.089 ms/op
     p(90.0000) =      2.593 ms/op
     p(95.0000) =      2.811 ms/op
     p(99.0000) =      4.596 ms/op
     p(99.9000) =     20.251 ms/op
     p(99.9900) =     21.532 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 4.672 ±(99.9%) 0.138 ms/op
Iteration   1: 3.108 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.059 ms/op
                 listUser·p0.50:   2.957 ms/op
                 listUser·p0.90:   3.744 ms/op
                 listUser·p0.95:   4.100 ms/op
                 listUser·p0.99:   5.709 ms/op
                 listUser·p0.999:  9.444 ms/op
                 listUser·p0.9999: 9.601 ms/op
                 listUser·p1.00:   9.601 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10306
  mean =      3.108 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 1.000,  1.500) = 4 
    [ 1.500,  2.000) = 15 
    [ 2.000,  2.500) = 334 
    [ 2.500,  3.000) = 5417 
    [ 3.000,  3.500) = 2956 
    [ 3.500,  4.000) = 951 
    [ 4.000,  4.500) = 447 
    [ 4.500,  5.000) = 53 
    [ 5.000,  5.500) = 8 
    [ 5.500,  6.000) = 45 
    [ 6.000,  6.500) = 6 
    [ 6.500,  7.000) = 5 
    [ 7.000,  7.500) = 1 
    [ 7.500,  8.000) = 0 
    [ 8.000,  8.500) = 37 
    [ 8.500,  9.000) = 12 
    [ 9.000,  9.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.059 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.744 ms/op
     p(95.0000) =      4.100 ms/op
     p(99.0000) =      5.709 ms/op
     p(99.9000) =      9.444 ms/op
     p(99.9900) =      9.601 ms/op
     p(99.9990) =      9.601 ms/op
     p(99.9999) =      9.601 ms/op
    p(100.0000) =      9.601 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.203          ops/ms
ClientSimple.existUser                       thrpt         13.301          ops/ms
ClientSimple.getUser                         thrpt         14.521          ops/ms
ClientSimple.listUser                        thrpt          8.436          ops/ms
ClientSimple.createUser                       avgt          2.241           ms/op
ClientSimple.existUser                        avgt          1.953           ms/op
ClientSimple.getUser                          avgt          1.961           ms/op
ClientSimple.listUser                         avgt          3.586           ms/op
ClientSimple.createUser                     sample  14463   2.219 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.679           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.982           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.740           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.974           ms/op
ClientSimple.createUser:createUser·p0.99    sample          9.001           ms/op
ClientSimple.createUser:createUser·p0.999   sample         20.760           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.692           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.692           ms/op
ClientSimple.existUser                      sample  16649   1.921 ± 0.030   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.666           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.745           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.286           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.576           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.119           ms/op
ClientSimple.existUser:existUser·p0.999     sample         24.161           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.347           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.347           ms/op
ClientSimple.getUser                        sample  14753   2.176 ± 0.027   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.676           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.089           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.593           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.811           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.596           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.251           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         21.532           ms/op
ClientSimple.getUser:getUser·p1.00          sample         21.594           ms/op
ClientSimple.listUser                       sample  10306   3.108 ± 0.021   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.059           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.957           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.744           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.100           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.709           ms/op
ClientSimple.listUser:listUser·p0.999       sample          9.444           ms/op
ClientSimple.listUser:listUser·p0.9999      sample          9.601           ms/op
ClientSimple.listUser:listUser·p1.00        sample          9.601           ms/op

Benchmark result is saved to 1719555195513.json
