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
# Warmup Iteration   1: 1.839 ops/ms
Iteration   1: 8.053 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  8.053 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.172 ops/ms
Iteration   1: 13.628 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.628 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:09
# Fork: 1 of 1
# Warmup Iteration   1: 6.141 ops/ms
Iteration   1: 14.225 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  14.225 ops/ms


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
# Warmup Iteration   1: 5.529 ops/ms
Iteration   1: 7.658 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.658 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:55
# Fork: 1 of 1
# Warmup Iteration   1: 3.622 ±(99.9%) 0.063 ms/op
Iteration   1: 2.229 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.229 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:48
# Fork: 1 of 1
# Warmup Iteration   1: 3.313 ±(99.9%) 0.094 ms/op
Iteration   1: 1.777 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.777 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:41
# Fork: 1 of 1
# Warmup Iteration   1: 3.192 ±(99.9%) 0.048 ms/op
Iteration   1: 1.915 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.915 ms/op


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

# Run progress: 58.33% complete, ETA 00:00:34
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.089 ms/op
Iteration   1: 3.690 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.690 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:27
# Fork: 1 of 1
# Warmup Iteration   1: 3.965 ±(99.9%) 0.111 ms/op
Iteration   1: 2.294 ±(99.9%) 0.029 ms/op
                 createUser·p0.00:   1.007 ms/op
                 createUser·p0.50:   2.122 ms/op
                 createUser·p0.90:   2.855 ms/op
                 createUser·p0.95:   3.060 ms/op
                 createUser·p0.99:   5.909 ms/op
                 createUser·p0.999:  14.647 ms/op
                 createUser·p0.9999: 16.295 ms/op
                 createUser·p1.00:   16.302 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14386
  mean =      2.294 ±(99.9%) 0.029 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 65 
    [ 1.250,  2.500) = 10876 
    [ 2.500,  3.750) = 3072 
    [ 3.750,  5.000) = 153 
    [ 5.000,  6.250) = 89 
    [ 6.250,  7.500) = 34 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 25 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 4 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.007 ms/op
     p(50.0000) =      2.122 ms/op
     p(90.0000) =      2.855 ms/op
     p(95.0000) =      3.060 ms/op
     p(99.0000) =      5.909 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     16.295 ms/op
     p(99.9990) =     16.302 ms/op
     p(99.9999) =     16.302 ms/op
    p(100.0000) =     16.302 ms/op


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

# Run progress: 75.00% complete, ETA 00:00:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.014 ±(99.9%) 0.062 ms/op
Iteration   1: 2.056 ±(99.9%) 0.052 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   1.860 ms/op
                 existUser·p0.90:   2.376 ms/op
                 existUser·p0.95:   2.601 ms/op
                 existUser·p0.99:   4.481 ms/op
                 existUser·p0.999:  44.501 ms/op
                 existUser·p0.9999: 45.445 ms/op
                 existUser·p1.00:   45.482 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15661
  mean =      2.056 ±(99.9%) 0.052 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 15535 
    [ 5.000, 10.000) = 31 
    [10.000, 15.000) = 23 
    [15.000, 20.000) = 35 
    [20.000, 25.000) = 7 
    [25.000, 30.000) = 3 
    [30.000, 35.000) = 5 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      1.860 ms/op
     p(90.0000) =      2.376 ms/op
     p(95.0000) =      2.601 ms/op
     p(99.0000) =      4.481 ms/op
     p(99.9000) =     44.501 ms/op
     p(99.9900) =     45.445 ms/op
     p(99.9990) =     45.482 ms/op
     p(99.9999) =     45.482 ms/op
    p(100.0000) =     45.482 ms/op


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
# Warmup Iteration   1: 3.264 ±(99.9%) 0.079 ms/op
Iteration   1: 2.119 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   0.375 ms/op
                 getUser·p0.50:   1.991 ms/op
                 getUser·p0.90:   2.810 ms/op
                 getUser·p0.95:   3.174 ms/op
                 getUser·p0.99:   4.660 ms/op
                 getUser·p0.999:  12.057 ms/op
                 getUser·p0.9999: 13.344 ms/op
                 getUser·p1.00:   13.386 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15111
  mean =      2.119 ±(99.9%) 0.021 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 128 
    [ 1.250,  2.500) = 11682 
    [ 2.500,  3.750) = 3050 
    [ 3.750,  5.000) = 168 
    [ 5.000,  6.250) = 38 
    [ 6.250,  7.500) = 13 
    [ 7.500,  8.750) = 0 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 7 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.375 ms/op
     p(50.0000) =      1.991 ms/op
     p(90.0000) =      2.810 ms/op
     p(95.0000) =      3.174 ms/op
     p(99.0000) =      4.660 ms/op
     p(99.9000) =     12.057 ms/op
     p(99.9900) =     13.344 ms/op
     p(99.9990) =     13.386 ms/op
     p(99.9999) =     13.386 ms/op
    p(100.0000) =     13.386 ms/op


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
# Warmup Iteration   1: 4.519 ±(99.9%) 0.135 ms/op
Iteration   1: 3.613 ±(99.9%) 0.053 ms/op
                 listUser·p0.00:   1.027 ms/op
                 listUser·p0.50:   3.564 ms/op
                 listUser·p0.90:   4.332 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   5.587 ms/op
                 listUser·p0.999:  26.315 ms/op
                 listUser·p0.9999: 29.655 ms/op
                 listUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 8861
  mean =      3.613 ±(99.9%) 0.053 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 538 
    [ 2.500,  5.000) = 8139 
    [ 5.000,  7.500) = 152 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.027 ms/op
     p(50.0000) =      3.564 ms/op
     p(90.0000) =      4.332 ms/op
     p(95.0000) =      4.620 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     26.315 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     29.655 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          8.053          ops/ms
ClientSimple.existUser                       thrpt         13.628          ops/ms
ClientSimple.getUser                         thrpt         14.225          ops/ms
ClientSimple.listUser                        thrpt          7.658          ops/ms
ClientSimple.createUser                       avgt          2.229           ms/op
ClientSimple.existUser                        avgt          1.777           ms/op
ClientSimple.getUser                          avgt          1.915           ms/op
ClientSimple.listUser                         avgt          3.690           ms/op
ClientSimple.createUser                     sample  14386   2.294 ± 0.029   ms/op
ClientSimple.createUser:createUser·p0.00    sample          1.007           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.122           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.855           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.060           ms/op
ClientSimple.createUser:createUser·p0.99    sample          5.909           ms/op
ClientSimple.createUser:createUser·p0.999   sample         14.647           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         16.295           ms/op
ClientSimple.createUser:createUser·p1.00    sample         16.302           ms/op
ClientSimple.existUser                      sample  15661   2.056 ± 0.052   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.771           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.860           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.376           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.601           ms/op
ClientSimple.existUser:existUser·p0.99      sample          4.481           ms/op
ClientSimple.existUser:existUser·p0.999     sample         44.501           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         45.445           ms/op
ClientSimple.existUser:existUser·p1.00      sample         45.482           ms/op
ClientSimple.getUser                        sample  15111   2.119 ± 0.021   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.375           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.991           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.810           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.174           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.660           ms/op
ClientSimple.getUser:getUser·p0.999         sample         12.057           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         13.344           ms/op
ClientSimple.getUser:getUser·p1.00          sample         13.386           ms/op
ClientSimple.listUser                       sample   8861   3.613 ± 0.053   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.027           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.564           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.332           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.620           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.587           ms/op
ClientSimple.listUser:listUser·p0.999       sample         26.315           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         29.655           ms/op
ClientSimple.listUser:listUser·p1.00        sample         29.655           ms/op

Benchmark result is saved to 1721456059883.json
