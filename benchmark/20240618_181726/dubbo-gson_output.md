# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.803 ops/ms
Iteration   1: 2.082 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  2.082 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 8.33% complete, ETA 00:01:17
# Fork: 1 of 1
# Warmup Iteration   1: 3.375 ops/ms
Iteration   1: 6.325 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  6.325 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 16.67% complete, ETA 00:01:10
# Fork: 1 of 1
# Warmup Iteration   1: 2.247 ops/ms
Iteration   1: 3.943 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  3.943 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 25.00% complete, ETA 00:01:03
# Fork: 1 of 1
# Warmup Iteration   1: 2.007 ops/ms
Iteration   1: 2.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  2.862 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 33.33% complete, ETA 00:00:56
# Fork: 1 of 1
# Warmup Iteration   1: 10.960 ±(99.9%) 0.296 ms/op
Iteration   1: 7.360 ±(99.9%) 0.065 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  7.360 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 41.67% complete, ETA 00:00:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.714 ±(99.9%) 0.071 ms/op
Iteration   1: 3.428 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  3.428 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 50.00% complete, ETA 00:00:42
# Fork: 1 of 1
# Warmup Iteration   1: 9.154 ±(99.9%) 0.153 ms/op
Iteration   1: 6.671 ±(99.9%) 0.085 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  6.671 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 58.33% complete, ETA 00:00:35
# Fork: 1 of 1
# Warmup Iteration   1: 15.014 ±(99.9%) 0.340 ms/op
Iteration   1: 9.442 ±(99.9%) 0.072 ms/op


Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  9.442 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.createUser

# Run progress: 66.67% complete, ETA 00:00:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.462 ±(99.9%) 0.295 ms/op
Iteration   1: 7.161 ±(99.9%) 0.127 ms/op
                 createUser·p0.00:   2.879 ms/op
                 createUser·p0.50:   6.619 ms/op
                 createUser·p0.90:   9.110 ms/op
                 createUser·p0.95:   11.043 ms/op
                 createUser·p0.99:   18.514 ms/op
                 createUser·p0.999:  25.609 ms/op
                 createUser·p0.9999: 26.313 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.createUser":
  N = 4475
  mean =      7.161 ±(99.9%) 0.127 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 384 
    [ 5.000,  7.500) = 2704 
    [ 7.500, 10.000) = 1099 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      2.879 ms/op
     p(50.0000) =      6.619 ms/op
     p(90.0000) =      9.110 ms/op
     p(95.0000) =     11.043 ms/op
     p(99.0000) =     18.514 ms/op
     p(99.9000) =     25.609 ms/op
     p(99.9900) =     26.313 ms/op
     p(99.9990) =     26.313 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.existUser

# Run progress: 75.00% complete, ETA 00:00:21
# Fork: 1 of 1
# Warmup Iteration   1: 5.497 ±(99.9%) 0.163 ms/op
Iteration   1: 3.383 ±(99.9%) 0.048 ms/op
                 existUser·p0.00:   1.100 ms/op
                 existUser·p0.50:   3.211 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.628 ms/op
                 existUser·p0.99:   7.326 ms/op
                 existUser·p0.999:  21.546 ms/op
                 existUser·p0.9999: 21.987 ms/op
                 existUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.existUser":
  N = 9472
  mean =      3.383 ±(99.9%) 0.048 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1156 
    [ 2.500,  5.000) = 8035 
    [ 5.000,  7.500) = 196 
    [ 7.500, 10.000) = 21 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.211 ms/op
     p(90.0000) =      4.284 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.326 ms/op
     p(99.9000) =     21.546 ms/op
     p(99.9900) =     21.987 ms/op
     p(99.9990) =     21.987 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 10.166 ±(99.9%) 0.336 ms/op
Iteration   1: 6.807 ±(99.9%) 0.092 ms/op
                 getUser·p0.00:   0.934 ms/op
                 getUser·p0.50:   6.529 ms/op
                 getUser·p0.90:   8.831 ms/op
                 getUser·p0.95:   10.043 ms/op
                 getUser·p0.99:   14.043 ms/op
                 getUser·p0.999:  18.491 ms/op
                 getUser·p0.9999: 20.185 ms/op
                 getUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.getUser":
  N = 4697
  mean =      6.807 ±(99.9%) 0.092 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2 
    [ 2.500,  5.000) = 549 
    [ 5.000,  7.500) = 2917 
    [ 7.500, 10.000) = 982 
    [10.000, 12.500) = 141 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.934 ms/op
     p(50.0000) =      6.529 ms/op
     p(90.0000) =      8.831 ms/op
     p(95.0000) =     10.043 ms/op
     p(99.0000) =     14.043 ms/op
     p(99.9000) =     18.491 ms/op
     p(99.9900) =     20.185 ms/op
     p(99.9990) =     20.185 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_412, OpenJDK 64-Bit Server VM, 25.412-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.412-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-gson_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientSimple.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 13.222 ±(99.9%) 0.459 ms/op
Iteration   1: 9.315 ±(99.9%) 0.157 ms/op
                 listUser·p0.00:   1.182 ms/op
                 listUser·p0.50:   9.257 ms/op
                 listUser·p0.90:   12.239 ms/op
                 listUser·p0.95:   13.533 ms/op
                 listUser·p0.99:   18.229 ms/op
                 listUser·p0.999:  25.053 ms/op
                 listUser·p0.9999: 25.231 ms/op
                 listUser·p1.00:   25.231 ms/op



Result "org.apache.dubbo.benchmark.ClientSimple.listUser":
  N = 3441
  mean =      9.315 ±(99.9%) 0.157 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 161 
    [ 5.000,  7.500) = 617 
    [ 7.500, 10.000) = 1417 
    [10.000, 12.500) = 937 
    [12.500, 15.000) = 214 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 12 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.182 ms/op
     p(50.0000) =      9.257 ms/op
     p(90.0000) =     12.239 ms/op
     p(95.0000) =     13.533 ms/op
     p(99.0000) =     18.229 ms/op
     p(99.9000) =     25.053 ms/op
     p(99.9900) =     25.231 ms/op
     p(99.9990) =     25.231 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:01:24

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                     Mode   Cnt   Score   Error   Units
ClientSimple.createUser                      thrpt         2.082          ops/ms
ClientSimple.existUser                       thrpt         6.325          ops/ms
ClientSimple.getUser                         thrpt         3.943          ops/ms
ClientSimple.listUser                        thrpt         2.862          ops/ms
ClientSimple.createUser                       avgt         7.360           ms/op
ClientSimple.existUser                        avgt         3.428           ms/op
ClientSimple.getUser                          avgt         6.671           ms/op
ClientSimple.listUser                         avgt         9.442           ms/op
ClientSimple.createUser                     sample  4475   7.161 ± 0.127   ms/op
ClientSimple.createUser:createUser·p0.00    sample         2.879           ms/op
ClientSimple.createUser:createUser·p0.50    sample         6.619           ms/op
ClientSimple.createUser:createUser·p0.90    sample         9.110           ms/op
ClientSimple.createUser:createUser·p0.95    sample        11.043           ms/op
ClientSimple.createUser:createUser·p0.99    sample        18.514           ms/op
ClientSimple.createUser:createUser·p0.999   sample        25.609           ms/op
ClientSimple.createUser:createUser·p0.9999  sample        26.313           ms/op
ClientSimple.createUser:createUser·p1.00    sample        26.313           ms/op
ClientSimple.existUser                      sample  9472   3.383 ± 0.048   ms/op
ClientSimple.existUser:existUser·p0.00      sample         1.100           ms/op
ClientSimple.existUser:existUser·p0.50      sample         3.211           ms/op
ClientSimple.existUser:existUser·p0.90      sample         4.284           ms/op
ClientSimple.existUser:existUser·p0.95      sample         4.628           ms/op
ClientSimple.existUser:existUser·p0.99      sample         7.326           ms/op
ClientSimple.existUser:existUser·p0.999     sample        21.546           ms/op
ClientSimple.existUser:existUser·p0.9999    sample        21.987           ms/op
ClientSimple.existUser:existUser·p1.00      sample        21.987           ms/op
ClientSimple.getUser                        sample  4697   6.807 ± 0.092   ms/op
ClientSimple.getUser:getUser·p0.00          sample         0.934           ms/op
ClientSimple.getUser:getUser·p0.50          sample         6.529           ms/op
ClientSimple.getUser:getUser·p0.90          sample         8.831           ms/op
ClientSimple.getUser:getUser·p0.95          sample        10.043           ms/op
ClientSimple.getUser:getUser·p0.99          sample        14.043           ms/op
ClientSimple.getUser:getUser·p0.999         sample        18.491           ms/op
ClientSimple.getUser:getUser·p0.9999        sample        20.185           ms/op
ClientSimple.getUser:getUser·p1.00          sample        20.185           ms/op
ClientSimple.listUser                       sample  3441   9.315 ± 0.157   ms/op
ClientSimple.listUser:listUser·p0.00        sample         1.182           ms/op
ClientSimple.listUser:listUser·p0.50        sample         9.257           ms/op
ClientSimple.listUser:listUser·p0.90        sample        12.239           ms/op
ClientSimple.listUser:listUser·p0.95        sample        13.533           ms/op
ClientSimple.listUser:listUser·p0.99        sample        18.229           ms/op
ClientSimple.listUser:listUser·p0.999       sample        25.053           ms/op
ClientSimple.listUser:listUser·p0.9999      sample        25.231           ms/op
ClientSimple.listUser:listUser·p1.00        sample        25.231           ms/op

Benchmark result is saved to 1718734372802.json
