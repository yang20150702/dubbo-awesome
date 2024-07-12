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
# Warmup Iteration   1: 2.065 ops/ms
Iteration   1: 7.524 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.524 ops/ms


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
# Warmup Iteration   1: 6.059 ops/ms
Iteration   1: 14.202 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  14.202 ops/ms


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
# Warmup Iteration   1: 6.459 ops/ms
Iteration   1: 14.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.537 ops/ms


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
# Warmup Iteration   1: 5.629 ops/ms
Iteration   1: 8.355 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.355 ops/ms


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
# Warmup Iteration   1: 4.485 ±(99.9%) 0.082 ms/op
Iteration   1: 2.334 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.334 ms/op


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
# Warmup Iteration   1: 2.810 ±(99.9%) 0.045 ms/op
Iteration   1: 1.912 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.912 ms/op


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
# Warmup Iteration   1: 3.105 ±(99.9%) 0.054 ms/op
Iteration   1: 1.824 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.824 ms/op


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
# Warmup Iteration   1: 4.231 ±(99.9%) 0.104 ms/op
Iteration   1: 3.190 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.190 ms/op


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
# Warmup Iteration   1: 3.400 ±(99.9%) 0.078 ms/op
Iteration   1: 2.203 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   2.003 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   2.912 ms/op
                 createUser·p0.99:   5.734 ms/op
                 createUser·p0.999:  22.774 ms/op
                 createUser·p0.9999: 23.400 ms/op
                 createUser·p1.00:   23.462 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14738
  mean =      2.203 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12848 
    [ 2.500,  5.000) = 1580 
    [ 5.000,  7.500) = 182 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 62 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.003 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.912 ms/op
     p(99.0000) =      5.734 ms/op
     p(99.9000) =     22.774 ms/op
     p(99.9900) =     23.400 ms/op
     p(99.9990) =     23.462 ms/op
     p(99.9999) =     23.462 ms/op
    p(100.0000) =     23.462 ms/op


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
# Warmup Iteration   1: 3.152 ±(99.9%) 0.074 ms/op
Iteration   1: 1.886 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   0.370 ms/op
                 existUser·p0.50:   1.741 ms/op
                 existUser·p0.90:   2.347 ms/op
                 existUser·p0.95:   2.535 ms/op
                 existUser·p0.99:   3.506 ms/op
                 existUser·p0.999:  19.921 ms/op
                 existUser·p0.9999: 21.407 ms/op
                 existUser·p1.00:   21.430 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17047
  mean =      1.886 ±(99.9%) 0.027 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16085 
    [ 2.500,  5.000) = 856 
    [ 5.000,  7.500) = 33 
    [ 7.500, 10.000) = 9 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.370 ms/op
     p(50.0000) =      1.741 ms/op
     p(90.0000) =      2.347 ms/op
     p(95.0000) =      2.535 ms/op
     p(99.0000) =      3.506 ms/op
     p(99.9000) =     19.921 ms/op
     p(99.9900) =     21.407 ms/op
     p(99.9990) =     21.430 ms/op
     p(99.9999) =     21.430 ms/op
    p(100.0000) =     21.430 ms/op


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
# Warmup Iteration   1: 3.507 ±(99.9%) 0.079 ms/op
Iteration   1: 2.150 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   2.097 ms/op
                 getUser·p0.90:   2.683 ms/op
                 getUser·p0.95:   2.834 ms/op
                 getUser·p0.99:   3.932 ms/op
                 getUser·p0.999:  11.239 ms/op
                 getUser·p0.9999: 13.837 ms/op
                 getUser·p1.00:   14.205 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14881
  mean =      2.150 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 148 
    [ 1.250,  2.500) = 11779 
    [ 2.500,  3.750) = 2781 
    [ 3.750,  5.000) = 94 
    [ 5.000,  6.250) = 47 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 19 
    [11.250, 12.500) = 11 
    [12.500, 13.750) = 1 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      2.097 ms/op
     p(90.0000) =      2.683 ms/op
     p(95.0000) =      2.834 ms/op
     p(99.0000) =      3.932 ms/op
     p(99.9000) =     11.239 ms/op
     p(99.9900) =     13.837 ms/op
     p(99.9990) =     14.205 ms/op
     p(99.9999) =     14.205 ms/op
    p(100.0000) =     14.205 ms/op


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
# Warmup Iteration   1: 4.320 ±(99.9%) 0.126 ms/op
Iteration   1: 3.567 ±(99.9%) 0.058 ms/op
                 listUser·p0.00:   1.194 ms/op
                 listUser·p0.50:   3.498 ms/op
                 listUser·p0.90:   4.235 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.694 ms/op
                 listUser·p0.999:  29.000 ms/op
                 listUser·p0.9999: 29.557 ms/op
                 listUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8972
  mean =      3.567 ±(99.9%) 0.058 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 748 
    [ 2.500,  5.000) = 7945 
    [ 5.000,  7.500) = 217 
    [ 7.500, 10.000) = 20 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.506 ms/op
     p(99.0000) =      6.694 ms/op
     p(99.9000) =     29.000 ms/op
     p(99.9900) =     29.557 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          7.524          ops/ms
ClientSimple.existUser                       thrpt         14.202          ops/ms
ClientSimple.getUser                         thrpt         14.537          ops/ms
ClientSimple.listUser                        thrpt          8.355          ops/ms
ClientSimple.createUser                       avgt          2.334           ms/op
ClientSimple.existUser                        avgt          1.912           ms/op
ClientSimple.getUser                          avgt          1.824           ms/op
ClientSimple.listUser                         avgt          3.190           ms/op
ClientSimple.createUser                     sample  14738   2.203 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.529           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.003           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.912           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.734           ms/op
ClientSimple.createUser:createUser·p0.999   sample         22.774           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         23.400           ms/op
ClientSimple.createUser:createUser·p1.00    sample         23.462           ms/op
ClientSimple.existUser                      sample  17047   1.886 ± 0.027   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.370           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.741           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.347           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.535           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.506           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.921           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.407           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.430           ms/op
ClientSimple.getUser                        sample  14881   2.150 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.568           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.097           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.683           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.834           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.932           ms/op
ClientSimple.getUser:getUser·p0.999         sample         11.239           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.837           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.205           ms/op
ClientSimple.listUser                       sample   8972   3.567 ± 0.058   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.194           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.498           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.235           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.506           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.694           ms/op
ClientSimple.listUser:listUser·p0.999       sample         29.000           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.557           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.557           ms/op

Benchmark result is saved to 1720764801312.json
