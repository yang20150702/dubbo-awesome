# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.777 ops/ms
Iteration   1: 6.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.660 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:18
# Fork: 1 of 1
# Warmup Iteration   1: 5.868 ops/ms
Iteration   1: 11.745 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  11.745 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 5.690 ops/ms
Iteration   1: 12.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.890 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 4.847 ops/ms
Iteration   1: 8.717 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.717 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 4.781 ±(99.9%) 0.080 ms/op
Iteration   1: 2.092 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.092 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 3.100 ±(99.9%) 0.050 ms/op
Iteration   1: 1.993 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.993 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.473 ±(99.9%) 0.054 ms/op
Iteration   1: 1.983 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.983 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 4.506 ±(99.9%) 0.072 ms/op
Iteration   1: 3.574 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.574 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 4.036 ±(99.9%) 0.115 ms/op
Iteration   1: 2.042 ±(99.9%) 0.030 ms/op
                 createUser·p0.00:   0.639 ms/op
                 createUser·p0.50:   1.888 ms/op
                 createUser·p0.90:   2.499 ms/op
                 createUser·p0.95:   2.671 ms/op
                 createUser·p0.99:   5.689 ms/op
                 createUser·p0.999:  16.876 ms/op
                 createUser·p0.9999: 21.263 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15659
  mean =      2.042 ±(99.9%) 0.030 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14097 
    [ 2.500,  5.000) = 1384 
    [ 5.000,  7.500) = 37 
    [ 7.500, 10.000) = 32 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 26 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.639 ms/op
     p(50.0000) =      1.888 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.671 ms/op
     p(99.0000) =      5.689 ms/op
     p(99.9000) =     16.876 ms/op
     p(99.9900) =     21.263 ms/op
     p(99.9990) =     21.856 ms/op
     p(99.9999) =     21.856 ms/op
    p(100.0000) =     21.856 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 3.028 ±(99.9%) 0.074 ms/op
Iteration   1: 1.720 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   1.642 ms/op
                 existUser·p0.90:   2.101 ms/op
                 existUser·p0.95:   2.294 ms/op
                 existUser·p0.99:   3.076 ms/op
                 existUser·p0.999:  18.166 ms/op
                 existUser·p0.9999: 18.827 ms/op
                 existUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 18621
  mean =      1.720 ±(99.9%) 0.022 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1851 
    [ 1.250,  2.500) = 16316 
    [ 2.500,  3.750) = 359 
    [ 3.750,  5.000) = 29 
    [ 5.000,  6.250) = 1 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 29 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      1.642 ms/op
     p(90.0000) =      2.101 ms/op
     p(95.0000) =      2.294 ms/op
     p(99.0000) =      3.076 ms/op
     p(99.9000) =     18.166 ms/op
     p(99.9900) =     18.827 ms/op
     p(99.9990) =     18.940 ms/op
     p(99.9999) =     18.940 ms/op
    p(100.0000) =     18.940 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 3.223 ±(99.9%) 0.077 ms/op
Iteration   1: 1.999 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   0.631 ms/op
                 getUser·p0.50:   1.901 ms/op
                 getUser·p0.90:   2.331 ms/op
                 getUser·p0.95:   2.601 ms/op
                 getUser·p0.99:   3.142 ms/op
                 getUser·p0.999:  21.228 ms/op
                 getUser·p0.9999: 22.184 ms/op
                 getUser·p1.00:   22.184 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 16187
  mean =      1.999 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15159 
    [ 2.500,  5.000) = 965 
    [ 5.000,  7.500) = 18 
    [ 7.500, 10.000) = 13 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.631 ms/op
     p(50.0000) =      1.901 ms/op
     p(90.0000) =      2.331 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      3.142 ms/op
     p(99.9000) =     21.228 ms/op
     p(99.9900) =     22.184 ms/op
     p(99.9990) =     22.184 ms/op
     p(99.9999) =     22.184 ms/op
    p(100.0000) =     22.184 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-kryo_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 4.558 ±(99.9%) 0.128 ms/op
Iteration   1: 2.963 ±(99.9%) 0.035 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   2.671 ms/op
                 listUser·p0.90:   3.867 ms/op
                 listUser·p0.95:   4.229 ms/op
                 listUser·p0.99:   5.555 ms/op
                 listUser·p0.999:  19.491 ms/op
                 listUser·p0.9999: 20.134 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10794
  mean =      2.963 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3455 
    [ 2.500,  5.000) = 7194 
    [ 5.000,  7.500) = 102 
    [ 7.500, 10.000) = 10 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      2.671 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.229 ms/op
     p(99.0000) =      5.555 ms/op
     p(99.9000) =     19.491 ms/op
     p(99.9900) =     20.134 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.660          ops/ms
ClientSimple.existUser                       thrpt         11.745          ops/ms
ClientSimple.getUser                         thrpt         12.890          ops/ms
ClientSimple.listUser                        thrpt          8.717          ops/ms
ClientSimple.createUser                       avgt          2.092           ms/op
ClientSimple.existUser                        avgt          1.993           ms/op
ClientSimple.getUser                          avgt          1.983           ms/op
ClientSimple.listUser                         avgt          3.574           ms/op
ClientSimple.createUser                     sample  15659   2.042 ± 0.030   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.639           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.888           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.499           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.671           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.689           ms/op
ClientSimple.createUser:createUser·p0.999   sample         16.876           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         21.263           ms/op
ClientSimple.createUser:createUser·p1.00    sample         21.856           ms/op
ClientSimple.existUser                      sample  18621   1.720 ± 0.022   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.675           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.642           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.101           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.294           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.076           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.166           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         18.827           ms/op
ClientSimple.existUser:existUser·p1.00      sample         18.940           ms/op
ClientSimple.getUser                        sample  16187   1.999 ± 0.025   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.631           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.901           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.331           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.601           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.142           ms/op
ClientSimple.getUser:getUser·p0.999         sample         21.228           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         22.184           ms/op
ClientSimple.getUser:getUser·p1.00          sample         22.184           ms/op
ClientSimple.listUser                       sample  10794   2.963 ± 0.035   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.909           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.671           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.867           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.229           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.555           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.491           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         20.134           ms/op
ClientSimple.listUser:listUser·p1.00        sample         20.152           ms/op

Benchmark result is saved to 1711282454930.json
