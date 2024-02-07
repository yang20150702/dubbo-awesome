# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 2.227 ops/ms
Iteration   1: 6.011 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  6.011 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.368 ops/ms
Iteration   1: 13.048 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  13.048 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ops/ms
Iteration   1: 8.898 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  8.898 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.054 ops/ms
Iteration   1: 3.786 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  3.786 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.783 ±(99.9%) 0.079 ms/op
Iteration   1: 3.442 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  3.442 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.164 ±(99.9%) 0.031 ms/op
Iteration   1: 1.853 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  1.853 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.679 ±(99.9%) 0.057 ms/op
Iteration   1: 2.989 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  2.989 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.903 ±(99.9%) 0.211 ms/op
Iteration   1: 7.771 ±(99.9%) 0.089 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  7.771 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 5.607 ±(99.9%) 0.191 ms/op
Iteration   1: 3.139 ±(99.9%) 0.048 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   2.859 ms/op
                 createUser·p0.90:   3.867 ms/op
                 createUser·p0.95:   4.334 ms/op
                 createUser·p0.99:   11.387 ms/op
                 createUser·p0.999:  16.199 ms/op
                 createUser·p0.9999: 17.921 ms/op
                 createUser·p1.00:   17.924 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 10191
  mean =      3.139 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 7 
    [ 1.250,  2.500) = 2009 
    [ 2.500,  3.750) = 6985 
    [ 3.750,  5.000) = 843 
    [ 5.000,  6.250) = 58 
    [ 6.250,  7.500) = 30 
    [ 7.500,  8.750) = 56 
    [ 8.750, 10.000) = 48 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 40 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 44 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 6 
    [17.500, 18.750) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      2.859 ms/op
     p(90.0000) =      3.867 ms/op
     p(95.0000) =      4.334 ms/op
     p(99.0000) =     11.387 ms/op
     p(99.9000) =     16.199 ms/op
     p(99.9900) =     17.921 ms/op
     p(99.9990) =     17.924 ms/op
     p(99.9999) =     17.924 ms/op
    p(100.0000) =     17.924 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.138 ±(99.9%) 0.071 ms/op
Iteration   1: 1.718 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   0.428 ms/op
                 existUser·p0.50:   1.604 ms/op
                 existUser·p0.90:   2.208 ms/op
                 existUser·p0.95:   2.396 ms/op
                 existUser·p0.99:   3.027 ms/op
                 existUser·p0.999:  16.663 ms/op
                 existUser·p0.9999: 16.974 ms/op
                 existUser·p1.00:   16.974 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 18668
  mean =      1.718 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1057 
    [ 1.250,  2.500) = 16981 
    [ 2.500,  3.750) = 513 
    [ 3.750,  5.000) = 81 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 28 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.604 ms/op
     p(90.0000) =      2.208 ms/op
     p(95.0000) =      2.396 ms/op
     p(99.0000) =      3.027 ms/op
     p(99.9000) =     16.663 ms/op
     p(99.9900) =     16.974 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     16.974 ms/op
    p(100.0000) =     16.974 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:13
# Fork: 1 of 1
# Warmup Iteration   1: 4.321 ±(99.9%) 0.089 ms/op
Iteration   1: 3.030 ±(99.9%) 0.033 ms/op
                 getUser·p0.00:   0.833 ms/op
                 getUser·p0.50:   2.884 ms/op
                 getUser·p0.90:   3.696 ms/op
                 getUser·p0.95:   4.051 ms/op
                 getUser·p0.99:   5.999 ms/op
                 getUser·p0.999:  17.105 ms/op
                 getUser·p0.9999: 22.844 ms/op
                 getUser·p1.00:   22.872 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 10566
  mean =      3.030 ±(99.9%) 0.033 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2161 
    [ 2.500,  5.000) = 8247 
    [ 5.000,  7.500) = 92 
    [ 7.500, 10.000) = 31 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      2.884 ms/op
     p(90.0000) =      3.696 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.999 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     22.844 ms/op
     p(99.9990) =     22.872 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_402, OpenJDK 64-Bit Server VM, 25.402-b06
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.402-6/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:06
# Fork: 1 of 1
# Warmup Iteration   1: 12.082 ±(99.9%) 0.475 ms/op
Iteration   1: 8.087 ±(99.9%) 0.112 ms/op
                 listUser·p0.00:   2.535 ms/op
                 listUser·p0.50:   7.799 ms/op
                 listUser·p0.90:   10.551 ms/op
                 listUser·p0.95:   11.928 ms/op
                 listUser·p0.99:   16.589 ms/op
                 listUser·p0.999:  20.134 ms/op
                 listUser·p0.9999: 20.906 ms/op
                 listUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 3950
  mean =      8.087 ±(99.9%) 0.112 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 106 
    [ 5.000,  7.500) = 1611 
    [ 7.500, 10.000) = 1699 
    [10.000, 12.500) = 395 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.535 ms/op
     p(50.0000) =      7.799 ms/op
     p(90.0000) =     10.551 ms/op
     p(95.0000) =     11.928 ms/op
     p(99.0000) =     16.589 ms/op
     p(99.9000) =     20.134 ms/op
     p(99.9900) =     20.906 ms/op
     p(99.9990) =     20.906 ms/op
     p(99.9999) =     20.906 ms/op
    p(100.0000) =     20.906 ms/op


# Run complete. Total time: 00:01:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode    Cnt   Score   Error   Units
Client.createUser                      thrpt          6.011          ops/ms
Client.existUser                       thrpt         13.048          ops/ms
Client.getUser                         thrpt          8.898          ops/ms
Client.listUser                        thrpt          3.786          ops/ms
Client.createUser                       avgt          3.442           ms/op
Client.existUser                        avgt          1.853           ms/op
Client.getUser                          avgt          2.989           ms/op
Client.listUser                         avgt          7.771           ms/op
Client.createUser                     sample  10191   3.139 ± 0.048   ms/op
Client.createUser:createUser·p0.00    sample          1.114           ms/op
Client.createUser:createUser·p0.50    sample          2.859           ms/op
Client.createUser:createUser·p0.90    sample          3.867           ms/op
Client.createUser:createUser·p0.95    sample          4.334           ms/op
Client.createUser:createUser·p0.99    sample         11.387           ms/op
Client.createUser:createUser·p0.999   sample         16.199           ms/op
Client.createUser:createUser·p0.9999  sample         17.921           ms/op
Client.createUser:createUser·p1.00    sample         17.924           ms/op
Client.existUser                      sample  18668   1.718 ± 0.018   ms/op
Client.existUser:existUser·p0.00      sample          0.428           ms/op
Client.existUser:existUser·p0.50      sample          1.604           ms/op
Client.existUser:existUser·p0.90      sample          2.208           ms/op
Client.existUser:existUser·p0.95      sample          2.396           ms/op
Client.existUser:existUser·p0.99      sample          3.027           ms/op
Client.existUser:existUser·p0.999     sample         16.663           ms/op
Client.existUser:existUser·p0.9999    sample         16.974           ms/op
Client.existUser:existUser·p1.00      sample         16.974           ms/op
Client.getUser                        sample  10566   3.030 ± 0.033   ms/op
Client.getUser:getUser·p0.00          sample          0.833           ms/op
Client.getUser:getUser·p0.50          sample          2.884           ms/op
Client.getUser:getUser·p0.90          sample          3.696           ms/op
Client.getUser:getUser·p0.95          sample          4.051           ms/op
Client.getUser:getUser·p0.99          sample          5.999           ms/op
Client.getUser:getUser·p0.999         sample         17.105           ms/op
Client.getUser:getUser·p0.9999        sample         22.844           ms/op
Client.getUser:getUser·p1.00          sample         22.872           ms/op
Client.listUser                       sample   3950   8.087 ± 0.112   ms/op
Client.listUser:listUser·p0.00        sample          2.535           ms/op
Client.listUser:listUser·p0.50        sample          7.799           ms/op
Client.listUser:listUser·p0.90        sample         10.551           ms/op
Client.listUser:listUser·p0.95        sample         11.928           ms/op
Client.listUser:listUser·p0.99        sample         16.589           ms/op
Client.listUser:listUser·p0.999       sample         20.134           ms/op
Client.listUser:listUser·p0.9999      sample         20.906           ms/op
Client.listUser:listUser·p1.00        sample         20.906           ms/op
