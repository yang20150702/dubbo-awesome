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
# Warmup Iteration   1: 1.576 ops/ms
Iteration   1: 6.537 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.537 ops/ms


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
# Warmup Iteration   1: 4.902 ops/ms
Iteration   1: 12.245 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.245 ops/ms


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
# Warmup Iteration   1: 4.987 ops/ms
Iteration   1: 11.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.248 ops/ms


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
# Warmup Iteration   1: 4.802 ops/ms
Iteration   1: 8.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.096 ops/ms


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
# Warmup Iteration   1: 4.222 ±(99.9%) 0.088 ms/op
Iteration   1: 2.281 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.281 ms/op


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
# Warmup Iteration   1: 3.306 ±(99.9%) 0.063 ms/op
Iteration   1: 1.880 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.880 ms/op


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
# Warmup Iteration   1: 3.530 ±(99.9%) 0.075 ms/op
Iteration   1: 1.901 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.901 ms/op


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
# Warmup Iteration   1: 4.623 ±(99.9%) 0.101 ms/op
Iteration   1: 3.399 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.399 ms/op


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
# Warmup Iteration   1: 3.677 ±(99.9%) 0.099 ms/op
Iteration   1: 2.114 ±(99.9%) 0.031 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   1.993 ms/op
                 createUser·p0.90:   2.576 ms/op
                 createUser·p0.95:   2.937 ms/op
                 createUser·p0.99:   4.005 ms/op
                 createUser·p0.999:  21.135 ms/op
                 createUser·p0.9999: 22.118 ms/op
                 createUser·p1.00:   22.118 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15111
  mean =      2.114 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13112 
    [ 2.500,  5.000) = 1882 
    [ 5.000,  7.500) = 52 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 19 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      1.993 ms/op
     p(90.0000) =      2.576 ms/op
     p(95.0000) =      2.937 ms/op
     p(99.0000) =      4.005 ms/op
     p(99.9000) =     21.135 ms/op
     p(99.9900) =     22.118 ms/op
     p(99.9990) =     22.118 ms/op
     p(99.9999) =     22.118 ms/op
    p(100.0000) =     22.118 ms/op


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
# Warmup Iteration   1: 3.087 ±(99.9%) 0.077 ms/op
Iteration   1: 2.091 ±(99.9%) 0.039 ms/op
                 existUser·p0.00:   0.326 ms/op
                 existUser·p0.50:   1.982 ms/op
                 existUser·p0.90:   2.564 ms/op
                 existUser·p0.95:   2.757 ms/op
                 existUser·p0.99:   3.753 ms/op
                 existUser·p0.999:  30.196 ms/op
                 existUser·p0.9999: 30.830 ms/op
                 existUser·p1.00:   30.900 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15375
  mean =      2.091 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13504 
    [ 2.500,  5.000) = 1795 
    [ 5.000,  7.500) = 12 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.326 ms/op
     p(50.0000) =      1.982 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.757 ms/op
     p(99.0000) =      3.753 ms/op
     p(99.9000) =     30.196 ms/op
     p(99.9900) =     30.830 ms/op
     p(99.9990) =     30.900 ms/op
     p(99.9999) =     30.900 ms/op
    p(100.0000) =     30.900 ms/op


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
# Warmup Iteration   1: 3.658 ±(99.9%) 0.087 ms/op
Iteration   1: 2.271 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.607 ms/op
                 getUser·p0.50:   2.183 ms/op
                 getUser·p0.90:   2.830 ms/op
                 getUser·p0.95:   3.113 ms/op
                 getUser·p0.99:   5.145 ms/op
                 getUser·p0.999:  12.280 ms/op
                 getUser·p0.9999: 13.864 ms/op
                 getUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14098
  mean =      2.271 ±(99.9%) 0.023 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 82 
    [ 1.250,  2.500) = 10626 
    [ 2.500,  3.750) = 3101 
    [ 3.750,  5.000) = 113 
    [ 5.000,  6.250) = 74 
    [ 6.250,  7.500) = 3 
    [ 7.500,  8.750) = 28 
    [ 8.750, 10.000) = 37 
    [10.000, 11.250) = 4 
    [11.250, 12.500) = 18 
    [12.500, 13.750) = 11 
    [13.750, 15.000) = 1 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      2.183 ms/op
     p(90.0000) =      2.830 ms/op
     p(95.0000) =      3.113 ms/op
     p(99.0000) =      5.145 ms/op
     p(99.9000) =     12.280 ms/op
     p(99.9900) =     13.864 ms/op
     p(99.9990) =     14.025 ms/op
     p(99.9999) =     14.025 ms/op
    p(100.0000) =     14.025 ms/op


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
# Warmup Iteration   1: 4.855 ±(99.9%) 0.131 ms/op
Iteration   1: 3.210 ±(99.9%) 0.039 ms/op
                 listUser·p0.00:   0.792 ms/op
                 listUser·p0.50:   2.929 ms/op
                 listUser·p0.90:   3.940 ms/op
                 listUser·p0.95:   4.309 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  20.806 ms/op
                 listUser·p0.9999: 21.593 ms/op
                 listUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10052
  mean =      3.210 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 534 
    [ 2.500,  5.000) = 9313 
    [ 5.000,  7.500) = 159 
    [ 7.500, 10.000) = 14 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      2.929 ms/op
     p(90.0000) =      3.940 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     20.806 ms/op
     p(99.9900) =     21.593 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.537          ops/ms
ClientSimple.existUser                       thrpt         12.245          ops/ms
ClientSimple.getUser                         thrpt         11.248          ops/ms
ClientSimple.listUser                        thrpt          8.096          ops/ms
ClientSimple.createUser                       avgt          2.281           ms/op
ClientSimple.existUser                        avgt          1.880           ms/op
ClientSimple.getUser                          avgt          1.901           ms/op
ClientSimple.listUser                         avgt          3.399           ms/op
ClientSimple.createUser                     sample  15111   2.114 ± 0.031   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.428           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.993           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.576           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.937           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.005           ms/op
ClientSimple.createUser:createUser·p0.999   sample         21.135           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         22.118           ms/op
ClientSimple.createUser:createUser·p1.00    sample         22.118           ms/op
ClientSimple.existUser                      sample  15375   2.091 ± 0.039   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.326           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.982           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.564           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.757           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.753           ms/op
ClientSimple.existUser:existUser·p0.999     sample         30.196           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         30.830           ms/op
ClientSimple.existUser:existUser·p1.00      sample         30.900           ms/op
ClientSimple.getUser                        sample  14098   2.271 ± 0.023   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.607           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.183           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.830           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.113           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.145           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.280           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.864           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.025           ms/op
ClientSimple.listUser                       sample  10052   3.210 ± 0.039   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.792           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.929           ms/op
ClientSimple.listUser:listUser·p0.90        sample          3.940           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.309           ms/op
ClientSimple.listUser:listUser·p0.99        sample          6.791           ms/op
ClientSimple.listUser:listUser·p0.999       sample         20.806           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         21.593           ms/op
ClientSimple.listUser:listUser·p1.00        sample         21.594           ms/op

Benchmark result is saved to 1723875164564.json
