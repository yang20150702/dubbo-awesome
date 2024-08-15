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
# Warmup Iteration   1: 1.001 ops/ms
Iteration   1: 4.521 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  4.521 ops/ms


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
# Warmup Iteration   1: 6.007 ops/ms
Iteration   1: 10.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  10.627 ops/ms


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
# Warmup Iteration   1: 5.120 ops/ms
Iteration   1: 11.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  11.106 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.637 ops/ms
Iteration   1: 8.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  8.771 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.028 ±(99.9%) 0.068 ms/op
Iteration   1: 2.021 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.021 ms/op


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
# Warmup Iteration   1: 3.295 ±(99.9%) 0.055 ms/op
Iteration   1: 1.860 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.860 ms/op


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
# Warmup Iteration   1: 3.457 ±(99.9%) 0.085 ms/op
Iteration   1: 2.465 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  2.465 ms/op


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
# Warmup Iteration   1: 4.698 ±(99.9%) 0.118 ms/op
Iteration   1: 3.193 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.193 ms/op


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
# Warmup Iteration   1: 3.580 ±(99.9%) 0.090 ms/op
Iteration   1: 2.068 ±(99.9%) 0.039 ms/op
                 createUser·p0.00:   0.660 ms/op
                 createUser·p0.50:   1.812 ms/op
                 createUser·p0.90:   2.486 ms/op
                 createUser·p0.95:   2.744 ms/op
                 createUser·p0.99:   6.155 ms/op
                 createUser·p0.999:  19.203 ms/op
                 createUser·p0.9999: 20.134 ms/op
                 createUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 15480
  mean =      2.068 ±(99.9%) 0.039 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14002 
    [ 2.500,  5.000) = 1240 
    [ 5.000,  7.500) = 100 
    [ 7.500, 10.000) = 1 
    [10.000, 12.500) = 9 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      1.812 ms/op
     p(90.0000) =      2.486 ms/op
     p(95.0000) =      2.744 ms/op
     p(99.0000) =      6.155 ms/op
     p(99.9000) =     19.203 ms/op
     p(99.9900) =     20.134 ms/op
     p(99.9990) =     20.152 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


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
# Warmup Iteration   1: 3.133 ±(99.9%) 0.071 ms/op
Iteration   1: 2.046 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   0.922 ms/op
                 existUser·p0.50:   1.964 ms/op
                 existUser·p0.90:   2.441 ms/op
                 existUser·p0.95:   2.703 ms/op
                 existUser·p0.99:   5.259 ms/op
                 existUser·p0.999:  13.312 ms/op
                 existUser·p0.9999: 21.373 ms/op
                 existUser·p1.00:   21.594 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 15618
  mean =      2.046 ±(99.9%) 0.025 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14319 
    [ 2.500,  5.000) = 1117 
    [ 5.000,  7.500) = 127 
    [ 7.500, 10.000) = 4 
    [10.000, 12.500) = 5 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.922 ms/op
     p(50.0000) =      1.964 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.703 ms/op
     p(99.0000) =      5.259 ms/op
     p(99.9000) =     13.312 ms/op
     p(99.9900) =     21.373 ms/op
     p(99.9990) =     21.594 ms/op
     p(99.9999) =     21.594 ms/op
    p(100.0000) =     21.594 ms/op


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
# Warmup Iteration   1: 3.588 ±(99.9%) 0.084 ms/op
Iteration   1: 2.129 ±(99.9%) 0.032 ms/op
                 getUser·p0.00:   0.616 ms/op
                 getUser·p0.50:   1.968 ms/op
                 getUser·p0.90:   2.441 ms/op
                 getUser·p0.95:   2.724 ms/op
                 getUser·p0.99:   5.055 ms/op
                 getUser·p0.999:  20.051 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   20.447 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 15095
  mean =      2.129 ±(99.9%) 0.032 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13839 
    [ 2.500,  5.000) = 1085 
    [ 5.000,  7.500) = 42 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 0 
    [12.500, 15.000) = 34 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.616 ms/op
     p(50.0000) =      1.968 ms/op
     p(90.0000) =      2.441 ms/op
     p(95.0000) =      2.724 ms/op
     p(99.0000) =      5.055 ms/op
     p(99.9000) =     20.051 ms/op
     p(99.9900) =     20.447 ms/op
     p(99.9990) =     20.447 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


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
# Warmup Iteration   1: 5.207 ±(99.9%) 0.156 ms/op
Iteration   1: 4.076 ±(99.9%) 0.169 ms/op
                 listUser·p0.00:   0.873 ms/op
                 listUser·p0.50:   3.600 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   5.112 ms/op
                 listUser·p0.99:   21.349 ms/op
                 listUser·p0.999:  58.009 ms/op
                 listUser·p0.9999: 63.308 ms/op
                 listUser·p1.00:   63.308 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 7846
  mean =      4.076 ±(99.9%) 0.169 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 7418 
    [ 5.000, 10.000) = 324 
    [10.000, 15.000) = 2 
    [15.000, 20.000) = 13 
    [20.000, 25.000) = 25 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 5 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 25 
    [50.000, 55.000) = 1 
    [55.000, 60.000) = 28 
    [60.000, 65.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.873 ms/op
     p(50.0000) =      3.600 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =     21.349 ms/op
     p(99.9000) =     58.009 ms/op
     p(99.9900) =     63.308 ms/op
     p(99.9990) =     63.308 ms/op
     p(99.9999) =     63.308 ms/op
    p(100.0000) =     63.308 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          4.521          ops/ms
ClientSimple.existUser                       thrpt         10.627          ops/ms
ClientSimple.getUser                         thrpt         11.106          ops/ms
ClientSimple.listUser                        thrpt          8.771          ops/ms
ClientSimple.createUser                       avgt          2.021           ms/op
ClientSimple.existUser                        avgt          1.860           ms/op
ClientSimple.getUser                          avgt          2.465           ms/op
ClientSimple.listUser                         avgt          3.193           ms/op
ClientSimple.createUser                     sample  15480   2.068 ± 0.039   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.660           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.812           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.486           ms/op
ClientSimple.createUser:createUser·p0.95    sample          2.744           ms/op
ClientSimple.createUser:createUser·p0.99    sample          6.155           ms/op
ClientSimple.createUser:createUser·p0.999   sample         19.203           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         20.134           ms/op
ClientSimple.createUser:createUser·p1.00    sample         20.152           ms/op
ClientSimple.existUser                      sample  15618   2.046 ± 0.025   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.922           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.964           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.441           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.703           ms/op
ClientSimple.existUser:existUser·p0.99      sample          5.259           ms/op
ClientSimple.existUser:existUser·p0.999     sample         13.312           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         21.373           ms/op
ClientSimple.existUser:existUser·p1.00      sample         21.594           ms/op
ClientSimple.getUser                        sample  15095   2.129 ± 0.032   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.616           ms/op
ClientSimple.getUser:getUser·p0.50          sample          1.968           ms/op
ClientSimple.getUser:getUser·p0.90          sample          2.441           ms/op
ClientSimple.getUser:getUser·p0.95          sample          2.724           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.055           ms/op
ClientSimple.getUser:getUser·p0.999         sample         20.051           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         20.447           ms/op
ClientSimple.getUser:getUser·p1.00          sample         20.447           ms/op
ClientSimple.listUser                       sample   7846   4.076 ± 0.169   ms/op
ClientSimple.listUser:listUser·p0.00        sample          0.873           ms/op
ClientSimple.listUser:listUser·p0.50        sample          3.600           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.514           ms/op
ClientSimple.listUser:listUser·p0.95        sample          5.112           ms/op
ClientSimple.listUser:listUser·p0.99        sample         21.349           ms/op
ClientSimple.listUser:listUser·p0.999       sample         58.009           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         63.308           ms/op
ClientSimple.listUser:listUser·p1.00        sample         63.308           ms/op

Benchmark result is saved to 1723702433376.json
