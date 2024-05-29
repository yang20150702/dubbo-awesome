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
# Warmup Iteration   1: 0.728 ops/ms
Iteration   1: 6.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  6.130 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:19
# Fork: 1 of 1
# Warmup Iteration   1: 6.071 ops/ms
Iteration   1: 13.186 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  13.186 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.652 ops/ms
Iteration   1: 12.106 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  12.106 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:04
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ops/ms
Iteration   1: 7.991 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  7.991 ops/ms


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

# Run progress: 33.33% complete, ETA 00:00:57
# Fork: 1 of 1
# Warmup Iteration   1: 4.421 ±(99.9%) 0.092 ms/op
Iteration   1: 2.287 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.287 ms/op


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
# Warmup Iteration   1: 3.584 ±(99.9%) 0.060 ms/op
Iteration   1: 1.969 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  1.969 ms/op


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
# Warmup Iteration   1: 3.338 ±(99.9%) 0.063 ms/op
Iteration   1: 1.849 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  1.849 ms/op


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
# Warmup Iteration   1: 4.654 ±(99.9%) 0.108 ms/op
Iteration   1: 3.127 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  3.127 ms/op


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
# Warmup Iteration   1: 3.635 ±(99.9%) 0.115 ms/op
Iteration   1: 2.285 ±(99.9%) 0.038 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   1.980 ms/op
                 createUser·p0.90:   2.879 ms/op
                 createUser·p0.95:   3.342 ms/op
                 createUser·p0.99:   8.053 ms/op
                 createUser·p0.999:  18.285 ms/op
                 createUser·p0.9999: 18.547 ms/op
                 createUser·p1.00:   18.547 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 14051
  mean =      2.285 ±(99.9%) 0.038 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 93 
    [ 1.250,  2.500) = 10832 
    [ 2.500,  3.750) = 2648 
    [ 3.750,  5.000) = 169 
    [ 5.000,  6.250) = 99 
    [ 6.250,  7.500) = 48 
    [ 7.500,  8.750) = 30 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 27 
    [13.750, 15.000) = 10 
    [15.000, 16.250) = 12 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      1.980 ms/op
     p(90.0000) =      2.879 ms/op
     p(95.0000) =      3.342 ms/op
     p(99.0000) =      8.053 ms/op
     p(99.9000) =     18.285 ms/op
     p(99.9900) =     18.547 ms/op
     p(99.9990) =     18.547 ms/op
     p(99.9999) =     18.547 ms/op
    p(100.0000) =     18.547 ms/op


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
# Warmup Iteration   1: 3.030 ±(99.9%) 0.077 ms/op
Iteration   1: 1.795 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   1.698 ms/op
                 existUser·p0.90:   2.167 ms/op
                 existUser·p0.95:   2.355 ms/op
                 existUser·p0.99:   3.300 ms/op
                 existUser·p0.999:  11.357 ms/op
                 existUser·p0.9999: 11.535 ms/op
                 existUser·p1.00:   11.715 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 17834
  mean =      1.795 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 226 
    [ 1.250,  2.500) = 17056 
    [ 2.500,  3.750) = 395 
    [ 3.750,  5.000) = 61 
    [ 5.000,  6.250) = 41 
    [ 6.250,  7.500) = 20 
    [ 7.500,  8.750) = 2 
    [ 8.750, 10.000) = 1 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 25 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      1.698 ms/op
     p(90.0000) =      2.167 ms/op
     p(95.0000) =      2.355 ms/op
     p(99.0000) =      3.300 ms/op
     p(99.9000) =     11.357 ms/op
     p(99.9900) =     11.535 ms/op
     p(99.9990) =     11.715 ms/op
     p(99.9999) =     11.715 ms/op
    p(100.0000) =     11.715 ms/op


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
# Warmup Iteration   1: 3.719 ±(99.9%) 0.090 ms/op
Iteration   1: 2.367 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   0.876 ms/op
                 getUser·p0.50:   2.179 ms/op
                 getUser·p0.90:   3.133 ms/op
                 getUser·p0.95:   3.449 ms/op
                 getUser·p0.99:   5.317 ms/op
                 getUser·p0.999:  19.628 ms/op
                 getUser·p0.9999: 19.792 ms/op
                 getUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 13754
  mean =      2.367 ±(99.9%) 0.035 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 91 
    [ 1.250,  2.500) = 9212 
    [ 2.500,  3.750) = 4000 
    [ 3.750,  5.000) = 271 
    [ 5.000,  6.250) = 103 
    [ 6.250,  7.500) = 8 
    [ 7.500,  8.750) = 4 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 0 
    [13.750, 15.000) = 0 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      2.179 ms/op
     p(90.0000) =      3.133 ms/op
     p(95.0000) =      3.449 ms/op
     p(99.0000) =      5.317 ms/op
     p(99.9000) =     19.628 ms/op
     p(99.9900) =     19.792 ms/op
     p(99.9990) =     19.792 ms/op
     p(99.9999) =     19.792 ms/op
    p(100.0000) =     19.792 ms/op


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
# Warmup Iteration   1: 4.605 ±(99.9%) 0.130 ms/op
Iteration   1: 3.140 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   2.961 ms/op
                 listUser·p0.90:   4.178 ms/op
                 listUser·p0.95:   4.473 ms/op
                 listUser·p0.99:   5.677 ms/op
                 listUser·p0.999:  10.093 ms/op
                 listUser·p0.9999: 10.819 ms/op
                 listUser·p1.00:   10.830 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 10170
  mean =      3.140 ±(99.9%) 0.028 ms/op

  Histogram, ms/op:
    [ 1.000,  2.000) = 317 
    [ 2.000,  3.000) = 5090 
    [ 3.000,  4.000) = 3372 
    [ 4.000,  5.000) = 1111 
    [ 5.000,  6.000) = 225 
    [ 6.000,  7.000) = 21 
    [ 7.000,  8.000) = 2 
    [ 8.000,  9.000) = 0 
    [ 9.000, 10.000) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      2.961 ms/op
     p(90.0000) =      4.178 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =     10.093 ms/op
     p(99.9900) =     10.819 ms/op
     p(99.9990) =     10.830 ms/op
     p(99.9999) =     10.830 ms/op
    p(100.0000) =     10.830 ms/op


# Run complete. Total time: 00:01:26

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode    Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt          6.130          ops/ms
ClientSimple.existUser                       thrpt         13.186          ops/ms
ClientSimple.getUser                         thrpt         12.106          ops/ms
ClientSimple.listUser                        thrpt          7.991          ops/ms
ClientSimple.createUser                       avgt          2.287           ms/op
ClientSimple.existUser                        avgt          1.969           ms/op
ClientSimple.getUser                          avgt          1.849           ms/op
ClientSimple.listUser                         avgt          3.127           ms/op
ClientSimple.createUser                     sample  14051   2.285 ± 0.038   ms/op
ClientSimple.createUser:createUser·p0.00    sample          0.706           ms/op
ClientSimple.createUser:createUser·p0.50    sample          1.980           ms/op
ClientSimple.createUser:createUser·p0.90    sample          2.879           ms/op
ClientSimple.createUser:createUser·p0.95    sample          3.342           ms/op
ClientSimple.createUser:createUser·p0.99    sample          8.053           ms/op
ClientSimple.createUser:createUser·p0.999   sample         18.285           ms/op
ClientSimple.createUser:createUser·p0.9999  sample         18.547           ms/op
ClientSimple.createUser:createUser·p1.00    sample         18.547           ms/op
ClientSimple.existUser                      sample  17834   1.795 ± 0.014   ms/op
ClientSimple.existUser:existUser·p0.00      sample          0.793           ms/op
ClientSimple.existUser:existUser·p0.50      sample          1.698           ms/op
ClientSimple.existUser:existUser·p0.90      sample          2.167           ms/op
ClientSimple.existUser:existUser·p0.95      sample          2.355           ms/op
ClientSimple.existUser:existUser·p0.99      sample          3.300           ms/op
ClientSimple.existUser:existUser·p0.999     sample         11.357           ms/op
ClientSimple.existUser:existUser·p0.9999    sample         11.535           ms/op
ClientSimple.existUser:existUser·p1.00      sample         11.715           ms/op
ClientSimple.getUser                        sample  13754   2.367 ± 0.035   ms/op
ClientSimple.getUser:getUser·p0.00          sample          0.876           ms/op
ClientSimple.getUser:getUser·p0.50          sample          2.179           ms/op
ClientSimple.getUser:getUser·p0.90          sample          3.133           ms/op
ClientSimple.getUser:getUser·p0.95          sample          3.449           ms/op
ClientSimple.getUser:getUser·p0.99          sample          5.317           ms/op
ClientSimple.getUser:getUser·p0.999         sample         19.628           ms/op
ClientSimple.getUser:getUser·p0.9999        sample         19.792           ms/op
ClientSimple.getUser:getUser·p1.00          sample         19.792           ms/op
ClientSimple.listUser                       sample  10170   3.140 ± 0.028   ms/op
ClientSimple.listUser:listUser·p0.00        sample          1.182           ms/op
ClientSimple.listUser:listUser·p0.50        sample          2.961           ms/op
ClientSimple.listUser:listUser·p0.90        sample          4.178           ms/op
ClientSimple.listUser:listUser·p0.95        sample          4.473           ms/op
ClientSimple.listUser:listUser·p0.99        sample          5.677           ms/op
ClientSimple.listUser:listUser·p0.999       sample         10.093           ms/op
ClientSimple.listUser:listUser·p0.9999      sample         10.819           ms/op
ClientSimple.listUser:listUser·p1.00        sample         10.830           ms/op

Benchmark result is saved to 1716943385520.json
