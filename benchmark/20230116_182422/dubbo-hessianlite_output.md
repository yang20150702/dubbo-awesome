# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.014 ops/ms
Iteration   1: 2.514 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  2.514 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:20
# Fork: 1 of 1
# Warmup Iteration   1: 2.803 ops/ms
Iteration   1: 6.248 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.248 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.538 ops/ms
Iteration   1: 4.381 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  4.381 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 0.867 ops/ms
Iteration   1: 1.270 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.270 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 17.496 ±(99.9%) 0.246 ms/op
Iteration   1: 7.628 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  7.628 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 8.547 ±(99.9%) 0.109 ms/op
Iteration   1: 4.480 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.480 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 13.653 ±(99.9%) 0.248 ms/op
Iteration   1: 5.460 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.460 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 28.807 ±(99.9%) 0.434 ms/op
Iteration   1: 16.221 ±(99.9%) 0.121 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  16.221 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 12.265 ±(99.9%) 0.344 ms/op
Iteration   1: 6.930 ±(99.9%) 0.123 ms/op
                 createUser·p0.00:   3.236 ms/op
                 createUser·p0.50:   6.578 ms/op
                 createUser·p0.90:   7.242 ms/op
                 createUser·p0.95:   8.651 ms/op
                 createUser·p0.99:   16.479 ms/op
                 createUser·p0.999:  29.963 ms/op
                 createUser·p0.9999: 34.144 ms/op
                 createUser·p1.00:   34.144 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 4602
  mean =      6.930 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 180 
    [ 5.000,  7.500) = 4067 
    [ 7.500, 10.000) = 141 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 77 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      3.236 ms/op
     p(50.0000) =      6.578 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.651 ms/op
     p(99.0000) =     16.479 ms/op
     p(99.9000) =     29.963 ms/op
     p(99.9900) =     34.144 ms/op
     p(99.9990) =     34.144 ms/op
     p(99.9999) =     34.144 ms/op
    p(100.0000) =     34.144 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 9.370 ±(99.9%) 0.273 ms/op
Iteration   1: 3.967 ±(99.9%) 0.077 ms/op
                 existUser·p0.00:   1.028 ms/op
                 existUser·p0.50:   3.588 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   7.601 ms/op
                 existUser·p0.99:   14.105 ms/op
                 existUser·p0.999:  17.986 ms/op
                 existUser·p0.9999: 22.479 ms/op
                 existUser·p1.00:   22.479 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 8101
  mean =      3.967 ±(99.9%) 0.077 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 393 
    [ 2.500,  5.000) = 7048 
    [ 5.000,  7.500) = 225 
    [ 7.500, 10.000) = 145 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.028 ms/op
     p(50.0000) =      3.588 ms/op
     p(90.0000) =      4.514 ms/op
     p(95.0000) =      7.601 ms/op
     p(99.0000) =     14.105 ms/op
     p(99.9000) =     17.986 ms/op
     p(99.9900) =     22.479 ms/op
     p(99.9990) =     22.479 ms/op
     p(99.9999) =     22.479 ms/op
    p(100.0000) =     22.479 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 11.848 ±(99.9%) 0.250 ms/op
Iteration   1: 5.442 ±(99.9%) 0.123 ms/op
                 getUser·p0.00:   2.163 ms/op
                 getUser·p0.50:   4.866 ms/op
                 getUser·p0.90:   7.135 ms/op
                 getUser·p0.95:   8.536 ms/op
                 getUser·p0.99:   21.908 ms/op
                 getUser·p0.999:  34.279 ms/op
                 getUser·p0.9999: 35.652 ms/op
                 getUser·p1.00:   35.652 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 5941
  mean =      5.442 ±(99.9%) 0.123 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 3128 
    [ 5.000,  7.500) = 2326 
    [ 7.500, 10.000) = 334 
    [10.000, 12.500) = 48 
    [12.500, 15.000) = 21 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.163 ms/op
     p(50.0000) =      4.866 ms/op
     p(90.0000) =      7.135 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     21.908 ms/op
     p(99.9000) =     34.279 ms/op
     p(99.9900) =     35.652 ms/op
     p(99.9990) =     35.652 ms/op
     p(99.9999) =     35.652 ms/op
    p(100.0000) =     35.652 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 26.836 ±(99.9%) 1.092 ms/op
Iteration   1: 19.313 ±(99.9%) 0.991 ms/op
                 listUser·p0.00:   6.578 ms/op
                 listUser·p0.50:   18.416 ms/op
                 listUser·p0.90:   20.500 ms/op
                 listUser·p0.95:   24.052 ms/op
                 listUser·p0.99:   101.012 ms/op
                 listUser·p0.999:  114.771 ms/op
                 listUser·p0.9999: 122.552 ms/op
                 listUser·p1.00:   122.552 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1666
  mean =     19.313 ±(99.9%) 0.991 ms/op

  Histogram, ms/op:
    [  0.000,  12.500) = 48 
    [ 12.500,  25.000) = 1537 
    [ 25.000,  37.500) = 44 
    [ 37.500,  50.000) = 5 
    [ 50.000,  62.500) = 0 
    [ 62.500,  75.000) = 0 
    [ 75.000,  87.500) = 0 
    [ 87.500, 100.000) = 13 
    [100.000, 112.500) = 18 
    [112.500, 125.000) = 1 
    [125.000, 137.500) = 0 
    [137.500, 150.000) = 0 
    [150.000, 162.500) = 0 
    [162.500, 175.000) = 0 
    [175.000, 187.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      6.578 ms/op
     p(50.0000) =     18.416 ms/op
     p(90.0000) =     20.500 ms/op
     p(95.0000) =     24.052 ms/op
     p(99.0000) =    101.012 ms/op
     p(99.9000) =    114.771 ms/op
     p(99.9900) =    122.552 ms/op
     p(99.9990) =    122.552 ms/op
     p(99.9999) =    122.552 ms/op
    p(100.0000) =    122.552 ms/op


# Run complete. Total time: 00:01:25

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt    Score   Error   Units
Client.createUser                      thrpt          2.514          ops/ms
Client.existUser                       thrpt          6.248          ops/ms
Client.getUser                         thrpt          4.381          ops/ms
Client.listUser                        thrpt          1.270          ops/ms
Client.createUser                       avgt          7.628           ms/op
Client.existUser                        avgt          4.480           ms/op
Client.getUser                          avgt          5.460           ms/op
Client.listUser                         avgt         16.221           ms/op
Client.createUser                     sample  4602    6.930 ± 0.123   ms/op
Client.createUser:createUser·p0.00    sample          3.236           ms/op
Client.createUser:createUser·p0.50    sample          6.578           ms/op
Client.createUser:createUser·p0.90    sample          7.242           ms/op
Client.createUser:createUser·p0.95    sample          8.651           ms/op
Client.createUser:createUser·p0.99    sample         16.479           ms/op
Client.createUser:createUser·p0.999   sample         29.963           ms/op
Client.createUser:createUser·p0.9999  sample         34.144           ms/op
Client.createUser:createUser·p1.00    sample         34.144           ms/op
Client.existUser                      sample  8101    3.967 ± 0.077   ms/op
Client.existUser:existUser·p0.00      sample          1.028           ms/op
Client.existUser:existUser·p0.50      sample          3.588           ms/op
Client.existUser:existUser·p0.90      sample          4.514           ms/op
Client.existUser:existUser·p0.95      sample          7.601           ms/op
Client.existUser:existUser·p0.99      sample         14.105           ms/op
Client.existUser:existUser·p0.999     sample         17.986           ms/op
Client.existUser:existUser·p0.9999    sample         22.479           ms/op
Client.existUser:existUser·p1.00      sample         22.479           ms/op
Client.getUser                        sample  5941    5.442 ± 0.123   ms/op
Client.getUser:getUser·p0.00          sample          2.163           ms/op
Client.getUser:getUser·p0.50          sample          4.866           ms/op
Client.getUser:getUser·p0.90          sample          7.135           ms/op
Client.getUser:getUser·p0.95          sample          8.536           ms/op
Client.getUser:getUser·p0.99          sample         21.908           ms/op
Client.getUser:getUser·p0.999         sample         34.279           ms/op
Client.getUser:getUser·p0.9999        sample         35.652           ms/op
Client.getUser:getUser·p1.00          sample         35.652           ms/op
Client.listUser                       sample  1666   19.313 ± 0.991   ms/op
Client.listUser:listUser·p0.00        sample          6.578           ms/op
Client.listUser:listUser·p0.50        sample         18.416           ms/op
Client.listUser:listUser·p0.90        sample         20.500           ms/op
Client.listUser:listUser·p0.95        sample         24.052           ms/op
Client.listUser:listUser·p0.99        sample        101.012           ms/op
Client.listUser:listUser·p0.999       sample        114.771           ms/op
Client.listUser:listUser·p0.9999      sample        122.552           ms/op
Client.listUser:listUser·p1.00        sample        122.552           ms/op
