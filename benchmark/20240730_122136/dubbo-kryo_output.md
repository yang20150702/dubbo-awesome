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
# Warmup Iteration   1: 1.641 ops/ms
Iteration   1: 6.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.581 ops/ms


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
# Warmup Iteration   1: 6.286 ops/ms
Iteration   1: 12.423 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  12.423 ops/ms


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
# Warmup Iteration   1: 5.951 ops/ms
Iteration   1: 12.670 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.670 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.213 ops/ms
Iteration   1: 9.363 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.363 ops/ms


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
# Warmup Iteration   1: 3.867 ±(99.9%) 0.064 ms/op
Iteration   1: 2.267 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.267 ms/op


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
# Warmup Iteration   1: 3.006 ±(99.9%) 0.048 ms/op
Iteration   1: 1.898 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.898 ms/op


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
# Warmup Iteration   1: 3.045 ±(99.9%) 0.060 ms/op
Iteration   1: 1.765 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.765 ms/op


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
# Warmup Iteration   1: 4.533 ±(99.9%) 0.096 ms/op
Iteration   1: 3.356 ±(99.9%) 0.024 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.356 ms/op


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
# Warmup Iteration   1: 3.404 ±(99.9%) 0.084 ms/op
Iteration   1: 2.108 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   0.835 ms/op
                 createUser·p0.50:   2.028 ms/op
                 createUser·p0.90:   2.568 ms/op
                 createUser·p0.95:   2.830 ms/op
                 createUser·p0.99:   3.848 ms/op
                 createUser·p0.999:  15.778 ms/op
                 createUser·p0.9999: 16.711 ms/op
                 createUser·p1.00:   16.744 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15164
  mean =      2.108 ±(99.9%) 0.026 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 115 
    [ 1.250,  2.500) = 13203 
    [ 2.500,  3.750) = 1687 
    [ 3.750,  5.000) = 91 
    [ 5.000,  6.250) = 4 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 26 
    [15.000, 16.250) = 36 
    [16.250, 17.500) = 2 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      2.028 ms/op
     p(90.0000) =      2.568 ms/op
     p(95.0000) =      2.830 ms/op
     p(99.0000) =      3.848 ms/op
     p(99.9000) =     15.778 ms/op
     p(99.9900) =     16.711 ms/op
     p(99.9990) =     16.744 ms/op
     p(99.9999) =     16.744 ms/op
    p(100.0000) =     16.744 ms/op


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
# Warmup Iteration   1: 3.023 ±(99.9%) 0.064 ms/op
Iteration   1: 2.015 ±(99.9%) 0.028 ms/op
                 existUser·p0.00:   0.197 ms/op
                 existUser·p0.50:   1.929 ms/op
                 existUser·p0.90:   2.589 ms/op
                 existUser·p0.95:   2.683 ms/op
                 existUser·p0.99:   4.321 ms/op
                 existUser·p0.999:  19.431 ms/op
                 existUser·p0.9999: 19.800 ms/op
                 existUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15857
  mean =      2.015 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 711 
    [ 1.250,  2.500) = 12971 
    [ 2.500,  3.750) = 1995 
    [ 3.750,  5.000) = 79 
    [ 5.000,  6.250) = 7 
    [ 6.250,  7.500) = 31 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 7 
    [12.500, 13.750) = 24 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.197 ms/op
     p(50.0000) =      1.929 ms/op
     p(90.0000) =      2.589 ms/op
     p(95.0000) =      2.683 ms/op
     p(99.0000) =      4.321 ms/op
     p(99.9000) =     19.431 ms/op
     p(99.9900) =     19.800 ms/op
     p(99.9990) =     19.857 ms/op
     p(99.9999) =     19.857 ms/op
    p(100.0000) =     19.857 ms/op


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
# Warmup Iteration   1: 3.294 ±(99.9%) 0.077 ms/op
Iteration   1: 2.140 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.557 ms/op
                 getUser·p0.50:   2.042 ms/op
                 getUser·p0.90:   2.585 ms/op
                 getUser·p0.95:   2.806 ms/op
                 getUser·p0.99:   3.467 ms/op
                 getUser·p0.999:  8.897 ms/op
                 getUser·p0.9999: 8.962 ms/op
                 getUser·p1.00:   8.962 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 14949
  mean =      2.140 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [0.000, 0.500) = 0 
    [0.500, 1.000) = 15 
    [1.000, 1.500) = 239 
    [1.500, 2.000) = 5785 
    [2.000, 2.500) = 7137 
    [2.500, 3.000) = 1378 
    [3.000, 3.500) = 250 
    [3.500, 4.000) = 61 
    [4.000, 4.500) = 9 
    [4.500, 5.000) = 6 
    [5.000, 5.500) = 1 
    [5.500, 6.000) = 16 
    [6.000, 6.500) = 4 
    [6.500, 7.000) = 2 
    [7.000, 7.500) = 1 
    [7.500, 8.000) = 6 
    [8.000, 8.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      0.557 ms/op
     p(50.0000) =      2.042 ms/op
     p(90.0000) =      2.585 ms/op
     p(95.0000) =      2.806 ms/op
     p(99.0000) =      3.467 ms/op
     p(99.9000) =      8.897 ms/op
     p(99.9900) =      8.962 ms/op
     p(99.9990) =      8.962 ms/op
     p(99.9999) =      8.962 ms/op
    p(100.0000) =      8.962 ms/op


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
# Warmup Iteration   1: 4.448 ±(99.9%) 0.134 ms/op
Iteration   1: 3.667 ±(99.9%) 0.045 ms/op
                 listUser·p0.00:   0.897 ms/op
                 listUser·p0.50:   3.609 ms/op
                 listUser·p0.90:   4.948 ms/op
                 listUser·p0.95:   5.284 ms/op
                 listUser·p0.99:   9.330 ms/op
                 listUser·p0.999:  14.836 ms/op
                 listUser·p0.9999: 24.150 ms/op
                 listUser·p1.00:   24.150 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8751
  mean =      3.667 ±(99.9%) 0.045 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1153 
    [ 2.500,  5.000) = 6775 
    [ 5.000,  7.500) = 703 
    [ 7.500, 10.000) = 49 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.897 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.948 ms/op
     p(95.0000) =      5.284 ms/op
     p(99.0000) =      9.330 ms/op
     p(99.9000) =     14.836 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     24.150 ms/op
     p(99.9999) =     24.150 ms/op
    p(100.0000) =     24.150 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.581          ops/ms
ClientSimple.existUser                       thrpt         12.423          ops/ms
ClientSimple.getUser                         thrpt         12.670          ops/ms
ClientSimple.listUser                        thrpt          9.363          ops/ms
ClientSimple.createUser                       avgt          2.267           ms/op
ClientSimple.existUser                        avgt          1.898           ms/op
ClientSimple.getUser                          avgt          1.765           ms/op
ClientSimple.listUser                         avgt          3.356           ms/op
ClientSimple.createUser                     sample  15164   2.108 ± 0.026   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.835           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.028           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.568           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.830           ms/op
ClientSimple.createUser:createUser·p0.99    sample          3.848           ms/op
ClientSimple.createUser:createUser·p0.999   sample         15.778           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.711           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.744           ms/op
ClientSimple.existUser                      sample  15857   2.015 ± 0.028   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.197           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.929           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.589           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.683           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.321           ms/op
ClientSimple.existUser:existUser·p0.999     sample         19.431           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         19.800           ms/op
ClientSimple.existUser:existUser·p1.00      sample         19.857           ms/op
ClientSimple.getUser                        sample  14949   2.140 ± 0.014   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.557           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.042           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.585           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.806           ms/op
ClientSimple.getUser:getUser·p0.99          sample          3.467           ms/op
ClientSimple.getUser:getUser·p0.999         sample          8.897           ms/op
ClientSimple.getUser:getUser·p0.9999        sample          8.962           ms/op
ClientSimple.getUser:getUser·p1.00          sample          8.962           ms/op
ClientSimple.listUser                       sample   8751   3.667 ± 0.045   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.897           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.609           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.948           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.284           ms/op
ClientSimple.listUser:listUser·p0.99        sample          9.330           ms/op
ClientSimple.listUser:listUser·p0.999       sample         14.836           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         24.150           ms/op
ClientSimple.listUser:listUser·p1.00        sample         24.150           ms/op

Benchmark result is saved to 1722341836859.json
