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
# Warmup Iteration   1: 1.692 ops/ms
Iteration   1: 4.955 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.955 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 5.614 ops/ms
Iteration   1: 13.287 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.287 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.406 ops/ms
Iteration   1: 11.845 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.845 ops/ms


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
# Warmup Iteration   1: 4.856 ops/ms
Iteration   1: 8.398 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.398 ops/ms


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
# Warmup Iteration   1: 4.600 ±(99.9%) 0.079 ms/op
Iteration   1: 2.192 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.192 ms/op


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
# Warmup Iteration   1: 3.145 ±(99.9%) 0.048 ms/op
Iteration   1: 2.070 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  2.070 ms/op


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
# Warmup Iteration   1: 3.494 ±(99.9%) 0.062 ms/op
Iteration   1: 2.282 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.282 ms/op


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
# Warmup Iteration   1: 4.221 ±(99.9%) 0.087 ms/op
Iteration   1: 3.432 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.432 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.086 ms/op
Iteration   1: 2.142 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   0.553 ms/op
                 createUser·p0.50:   2.083 ms/op
                 createUser·p0.90:   2.564 ms/op
                 createUser·p0.95:   2.798 ms/op
                 createUser·p0.99:   4.437 ms/op
                 createUser·p0.999:  17.105 ms/op
                 createUser·p0.9999: 19.318 ms/op
                 createUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14942
  mean =      2.142 ±(99.9%) 0.024 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 276 
    [ 1.250,  2.500) = 12714 
    [ 2.500,  3.750) = 1729 
    [ 3.750,  5.000) = 163 
    [ 5.000,  6.250) = 3 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 1 
    [ 8.750, 10.000) = 16 
    [10.000, 11.250) = 6 
    [11.250, 12.500) = 2 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 25 
    [17.500, 18.750) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      2.083 ms/op
     p(90.0000) =      2.564 ms/op
     p(95.0000) =      2.798 ms/op
     p(99.0000) =      4.437 ms/op
     p(99.9000) =     17.105 ms/op
     p(99.9900) =     19.318 ms/op
     p(99.9990) =     19.399 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


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
# Warmup Iteration   1: 2.945 ±(99.9%) 0.069 ms/op
Iteration   1: 1.909 ±(99.9%) 0.031 ms/op
                 existUser·p0.00:   0.474 ms/op
                 existUser·p0.50:   1.704 ms/op
                 existUser·p0.90:   2.253 ms/op
                 existUser·p0.95:   2.884 ms/op
                 existUser·p0.99:   5.063 ms/op
                 existUser·p0.999:  23.503 ms/op
                 existUser·p0.9999: 24.226 ms/op
                 existUser·p1.00:   24.248 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 16742
  mean =      1.909 ±(99.9%) 0.031 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15694 
    [ 2.500,  5.000) = 864 
    [ 5.000,  7.500) = 120 
    [ 7.500, 10.000) = 0 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      1.704 ms/op
     p(90.0000) =      2.253 ms/op
     p(95.0000) =      2.884 ms/op
     p(99.0000) =      5.063 ms/op
     p(99.9000) =     23.503 ms/op
     p(99.9900) =     24.226 ms/op
     p(99.9990) =     24.248 ms/op
     p(99.9999) =     24.248 ms/op
    p(100.0000) =     24.248 ms/op


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
# Warmup Iteration   1: 3.379 ±(99.9%) 0.077 ms/op
Iteration   1: 2.076 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   0.588 ms/op
                 getUser·p0.50:   1.915 ms/op
                 getUser·p0.90:   2.650 ms/op
                 getUser·p0.95:   2.949 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  10.125 ms/op
                 getUser·p0.9999: 10.680 ms/op
                 getUser·p1.00:   10.715 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15398
  mean =      2.076 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 155 
    [ 1.250,  2.500) = 12787 
    [ 2.500,  3.750) = 2164 
    [ 3.750,  5.000) = 161 
    [ 5.000,  6.250) = 94 
    [ 6.250,  7.500) = 0 
    [ 7.500,  8.750) = 5 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 29 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.588 ms/op
     p(50.0000) =      1.915 ms/op
     p(90.0000) =      2.650 ms/op
     p(95.0000) =      2.949 ms/op
     p(99.0000) =      4.784 ms/op
     p(99.9000) =     10.125 ms/op
     p(99.9900) =     10.680 ms/op
     p(99.9990) =     10.715 ms/op
     p(99.9999) =     10.715 ms/op
    p(100.0000) =     10.715 ms/op


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
# Warmup Iteration   1: 4.507 ±(99.9%) 0.131 ms/op
Iteration   1: 3.424 ±(99.9%) 0.051 ms/op
                 listUser·p0.00:   1.004 ms/op
                 listUser·p0.50:   3.211 ms/op
                 listUser·p0.90:   4.076 ms/op
                 listUser·p0.95:   4.514 ms/op
                 listUser·p0.99:   7.165 ms/op
                 listUser·p0.999:  23.231 ms/op
                 listUser·p0.9999: 23.855 ms/op
                 listUser·p1.00:   23.855 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 9341
  mean =      3.424 ±(99.9%) 0.051 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 699 
    [ 2.500,  5.000) = 8273 
    [ 5.000,  7.500) = 290 
    [ 7.500, 10.000) = 15 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.004 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.076 ms/op
     p(95.0000) =      4.514 ms/op
     p(99.0000) =      7.165 ms/op
     p(99.9000) =     23.231 ms/op
     p(99.9900) =     23.855 ms/op
     p(99.9990) =     23.855 ms/op
     p(99.9999) =     23.855 ms/op
    p(100.0000) =     23.855 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.955          ops/ms
ClientSimple.existUser                       thrpt         13.287          ops/ms
ClientSimple.getUser                         thrpt         11.845          ops/ms
ClientSimple.listUser                        thrpt          8.398          ops/ms
ClientSimple.createUser                       avgt          2.192           ms/op
ClientSimple.existUser                        avgt          2.070           ms/op
ClientSimple.getUser                          avgt          2.282           ms/op
ClientSimple.listUser                         avgt          3.432           ms/op
ClientSimple.createUser                     sample  14942   2.142 ± 0.024   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.553           ms/op
ClientSimple.createUser:createUser·p0.50    sample          2.083           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.564           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.798           ms/op
ClientSimple.createUser:createUser·p0.99    sample          4.437           ms/op
ClientSimple.createUser:createUser·p0.999   sample         17.105           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         19.318           ms/op
ClientSimple.createUser:createUser·p1.00    sample         19.399           ms/op
ClientSimple.existUser                      sample  16742   1.909 ± 0.031   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.474           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.704           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.253           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.884           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.063           ms/op
ClientSimple.existUser:existUser·p0.999     sample         23.503           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         24.226           ms/op
ClientSimple.existUser:existUser·p1.00      sample         24.248           ms/op
ClientSimple.getUser                        sample  15398   2.076 ± 0.018   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.588           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.915           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.650           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.949           ms/op
ClientSimple.getUser:getUser·p0.99          sample          4.784           ms/op
ClientSimple.getUser:getUser·p0.999         sample         10.125           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         10.680           ms/op
ClientSimple.getUser:getUser·p1.00          sample         10.715           ms/op
ClientSimple.listUser                       sample   9341   3.424 ± 0.051   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.004           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.211           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.076           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.99        sample          7.165           ms/op
ClientSimple.listUser:listUser·p0.999       sample         23.231           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         23.855           ms/op
ClientSimple.listUser:listUser·p1.00        sample         23.855           ms/op

Benchmark result is saved to 1722190336563.json
