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
# Warmup Iteration   1: 1.769 ops/ms
Iteration   1: 6.382 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.382 ops/ms


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
# Warmup Iteration   1: 6.164 ops/ms
Iteration   1: 10.945 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.945 ops/ms


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
# Warmup Iteration   1: 6.217 ops/ms
Iteration   1: 12.888 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.888 ops/ms


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
# Warmup Iteration   1: 3.861 ops/ms
Iteration   1: 8.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.593 ops/ms


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.067 ms/op
Iteration   1: 2.088 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.088 ms/op


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
# Warmup Iteration   1: 3.172 ±(99.9%) 0.054 ms/op
Iteration   1: 1.922 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.922 ms/op


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
# Warmup Iteration   1: 3.301 ±(99.9%) 0.055 ms/op
Iteration   1: 2.101 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.101 ms/op


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
# Warmup Iteration   1: 4.358 ±(99.9%) 0.082 ms/op
Iteration   1: 3.106 ±(99.9%) 0.082 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.106 ms/op


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
# Warmup Iteration   1: 3.519 ±(99.9%) 0.102 ms/op
Iteration   1: 2.119 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   0.420 ms/op
                 createUser·p0.50:   1.956 ms/op
                 createUser·p0.90:   2.605 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   7.152 ms/op
                 createUser·p0.999:  15.183 ms/op
                 createUser·p0.9999: 16.365 ms/op
                 createUser·p1.00:   16.564 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15274
  mean =      2.119 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 403 
    [ 1.250,  2.500) = 12675 
    [ 2.500,  3.750) = 1832 
    [ 3.750,  5.000) = 140 
    [ 5.000,  6.250) = 37 
    [ 6.250,  7.500) = 46 
    [ 7.500,  8.750) = 26 
    [ 8.750, 10.000) = 51 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 5 
    [13.750, 15.000) = 24 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 1 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.420 ms/op
     p(50.0000) =      1.956 ms/op
     p(90.0000) =      2.605 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      7.152 ms/op
     p(99.9000) =     15.183 ms/op
     p(99.9900) =     16.365 ms/op
     p(99.9990) =     16.564 ms/op
     p(99.9999) =     16.564 ms/op
    p(100.0000) =     16.564 ms/op


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
# Warmup Iteration   1: 3.013 ±(99.9%) 0.076 ms/op
Iteration   1: 2.044 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.683 ms/op
                 existUser·p0.50:   1.974 ms/op
                 existUser·p0.90:   2.499 ms/op
                 existUser·p0.95:   2.744 ms/op
                 existUser·p0.99:   3.755 ms/op
                 existUser·p0.999:  18.536 ms/op
                 existUser·p0.9999: 19.680 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15667
  mean =      2.044 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 591 
    [ 1.250,  2.500) = 13517 
    [ 2.500,  3.750) = 1403 
    [ 3.750,  5.000) = 86 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 2 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 18 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.683 ms/op
     p(50.0000) =      1.974 ms/op
     p(90.0000) =      2.499 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      3.755 ms/op
     p(99.9000) =     18.536 ms/op
     p(99.9900) =     19.680 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 3.243 ±(99.9%) 0.074 ms/op
Iteration   1: 1.865 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.550 ms/op
                 getUser·p0.50:   1.788 ms/op
                 getUser·p0.90:   2.265 ms/op
                 getUser·p0.95:   2.462 ms/op
                 getUser·p0.99:   3.113 ms/op
                 getUser·p0.999:  13.743 ms/op
                 getUser·p0.9999: 13.966 ms/op
                 getUser·p1.00:   14.025 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 17221
  mean =      1.865 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 379 
    [ 1.250,  2.500) = 16100 
    [ 2.500,  3.750) = 674 
    [ 3.750,  5.000) = 18 
    [ 5.000,  6.250) = 2 
    [ 6.250,  7.500) = 15 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 17 
    [13.750, 15.000) = 15 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.550 ms/op
     p(50.0000) =      1.788 ms/op
     p(90.0000) =      2.265 ms/op
     p(95.0000) =      2.462 ms/op
     p(99.0000) =      3.113 ms/op
     p(99.9000) =     13.743 ms/op
     p(99.9900) =     13.966 ms/op
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
# Warmup Iteration   1: 4.091 ±(99.9%) 0.114 ms/op
Iteration   1: 3.297 ±(99.9%) 0.040 ms/op
                 listUser·p0.00:   1.026 ms/op
                 listUser·p0.50:   3.109 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.456 ms/op
                 listUser·p0.99:   5.947 ms/op
                 listUser·p0.999:  19.474 ms/op
                 listUser·p0.9999: 19.726 ms/op
                 listUser·p1.00:   19.726 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9709
  mean =      3.297 ±(99.9%) 0.040 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3 
    [ 1.250,  2.500) = 1863 
    [ 2.500,  3.750) = 4975 
    [ 3.750,  5.000) = 2640 
    [ 5.000,  6.250) = 179 
    [ 6.250,  7.500) = 17 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.026 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      4.219 ms/op
     p(95.0000) =      4.456 ms/op
     p(99.0000) =      5.947 ms/op
     p(99.9000) =     19.474 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     19.726 ms/op
     p(99.9999) =     19.726 ms/op
    p(100.0000) =     19.726 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.382          ops/ms
ClientSimple.existUser                       thrpt         10.945          ops/ms
ClientSimple.getUser                         thrpt         12.888          ops/ms
ClientSimple.listUser                        thrpt          8.593          ops/ms
ClientSimple.createUser                       avgt          2.088           ms/op
ClientSimple.existUser                        avgt          1.922           ms/op
ClientSimple.getUser                          avgt          2.101           ms/op
ClientSimple.listUser                         avgt          3.106           ms/op
ClientSimple.createUser                     sample  15274   2.119 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.420           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.956           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.605           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          7.152           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.183           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.365           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.564           ms/op
ClientSimple.existUser                      sample  15667   2.044 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.683           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.974           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.499           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.744           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.755           ms/op
ClientSimple.existUser:existUser·p0.999     sample         18.536           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.680           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.792           ms/op
ClientSimple.getUser                        sample  17221   1.865 ± 0.016   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.550           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.788           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.265           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.462           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.113           ms/op
ClientSimple.getUser:getUser·p0.999         sample         13.743           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.966           ms/op
ClientSimple.getUser:getUser·p1.00          sample         14.025           ms/op
ClientSimple.listUser                       sample   9709   3.297 ± 0.040   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.026           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.109           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.219           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.456           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.947           ms/op
ClientSimple.listUser:listUser·p0.999       sample         19.474           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         19.726           ms/op
ClientSimple.listUser:listUser·p1.00        sample         19.726           ms/op

Benchmark result is saved to 1722276774377.json
