# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 0.00% complete, ETA 00:00:24
# Fork: 1 of 1
# Warmup Iteration   1: 0.499 ops/ms
Iteration   1: 1.275 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.275 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 8.33% complete, ETA 00:01:23
# Fork: 1 of 1
# Warmup Iteration   1: 2.248 ops/ms
Iteration   1: 4.484 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.484 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 16.67% complete, ETA 00:01:14
# Fork: 1 of 1
# Warmup Iteration   1: 1.597 ops/ms
Iteration   1: 3.825 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.825 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 25.00% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 0.734 ops/ms
Iteration   1: 1.040 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  1.040 ops/ms


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 33.33% complete, ETA 00:00:59
# Fork: 1 of 1
# Warmup Iteration   1: 25.263 ±(99.9%) 0.482 ms/op
Iteration   1: 16.319 ±(99.9%) 0.093 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  16.319 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 41.67% complete, ETA 00:00:51
# Fork: 1 of 1
# Warmup Iteration   1: 15.752 ±(99.9%) 0.179 ms/op
Iteration   1: 5.956 ±(99.9%) 0.032 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  5.956 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 50.00% complete, ETA 00:00:44
# Fork: 1 of 1
# Warmup Iteration   1: 21.256 ±(99.9%) 0.402 ms/op
Iteration   1: 5.705 ±(99.9%) 0.051 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  5.705 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 58.33% complete, ETA 00:00:37
# Fork: 1 of 1
# Warmup Iteration   1: 35.406 ±(99.9%) 0.941 ms/op
Iteration   1: 22.426 ±(99.9%) 0.166 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  22.426 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.createUser

# Run progress: 66.67% complete, ETA 00:00:29
# Fork: 1 of 1
# Warmup Iteration   1: 18.138 ±(99.9%) 0.763 ms/op
Iteration   1: 8.602 ±(99.9%) 0.242 ms/op
                 createUser·p0.00:   3.052 ms/op
                 createUser·p0.50:   7.897 ms/op
                 createUser·p0.90:   13.271 ms/op
                 createUser·p0.95:   17.105 ms/op
                 createUser·p0.99:   22.479 ms/op
                 createUser·p0.999:  47.055 ms/op
                 createUser·p0.9999: 47.383 ms/op
                 createUser·p1.00:   47.383 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3719
  mean =      8.602 ±(99.9%) 0.242 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 411 
    [ 5.000, 10.000) = 2675 
    [10.000, 15.000) = 374 
    [15.000, 20.000) = 163 
    [20.000, 25.000) = 64 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 25 
    [40.000, 45.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      3.052 ms/op
     p(50.0000) =      7.897 ms/op
     p(90.0000) =     13.271 ms/op
     p(95.0000) =     17.105 ms/op
     p(99.0000) =     22.479 ms/op
     p(99.9000) =     47.055 ms/op
     p(99.9900) =     47.383 ms/op
     p(99.9990) =     47.383 ms/op
     p(99.9999) =     47.383 ms/op
    p(100.0000) =     47.383 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.existUser

# Run progress: 75.00% complete, ETA 00:00:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.138 ±(99.9%) 0.349 ms/op
Iteration   1: 4.449 ±(99.9%) 0.107 ms/op
                 existUser·p0.00:   1.284 ms/op
                 existUser·p0.50:   3.903 ms/op
                 existUser·p0.90:   5.931 ms/op
                 existUser·p0.95:   9.105 ms/op
                 existUser·p0.99:   15.614 ms/op
                 existUser·p0.999:  30.474 ms/op
                 existUser·p0.9999: 30.999 ms/op
                 existUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 7205
  mean =      4.449 ±(99.9%) 0.107 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 428 
    [ 2.500,  5.000) = 5112 
    [ 5.000,  7.500) = 1219 
    [ 7.500, 10.000) = 147 
    [10.000, 12.500) = 186 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 14 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.284 ms/op
     p(50.0000) =      3.903 ms/op
     p(90.0000) =      5.931 ms/op
     p(95.0000) =      9.105 ms/op
     p(99.0000) =     15.614 ms/op
     p(99.9000) =     30.474 ms/op
     p(99.9900) =     30.999 ms/op
     p(99.9990) =     30.999 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.getUser

# Run progress: 83.33% complete, ETA 00:00:14
# Fork: 1 of 1
# Warmup Iteration   1: 17.088 ±(99.9%) 0.475 ms/op
Iteration   1: 6.396 ±(99.9%) 0.107 ms/op
                 getUser·p0.00:   1.569 ms/op
                 getUser·p0.50:   5.833 ms/op
                 getUser·p0.90:   8.870 ms/op
                 getUser·p0.95:   9.667 ms/op
                 getUser·p0.99:   14.385 ms/op
                 getUser·p0.999:  25.985 ms/op
                 getUser·p0.9999: 26.247 ms/op
                 getUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4995
  mean =      6.396 ±(99.9%) 0.107 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 975 
    [ 5.000,  7.500) = 2958 
    [ 7.500, 10.000) = 847 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.569 ms/op
     p(50.0000) =      5.833 ms/op
     p(90.0000) =      8.870 ms/op
     p(95.0000) =      9.667 ms/op
     p(99.0000) =     14.385 ms/op
     p(99.9000) =     25.985 ms/op
     p(99.9900) =     26.247 ms/op
     p(99.9990) =     26.247 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-hessianlite_output.md
# Warmup: 1 iterations, 1 s each
# Measurement: 1 iterations, 1 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.Client.listUser

# Run progress: 91.67% complete, ETA 00:00:07
# Fork: 1 of 1
# Warmup Iteration   1: 33.807 ±(99.9%) 1.135 ms/op
Iteration   1: 23.410 ±(99.9%) 0.493 ms/op
                 listUser·p0.00:   3.531 ms/op
                 listUser·p0.50:   21.823 ms/op
                 listUser·p0.90:   34.315 ms/op
                 listUser·p0.95:   36.064 ms/op
                 listUser·p0.99:   40.632 ms/op
                 listUser·p0.999:  41.540 ms/op
                 listUser·p0.9999: 41.812 ms/op
                 listUser·p1.00:   41.812 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1376
  mean =     23.410 ±(99.9%) 0.493 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2 
    [ 5.000, 10.000) = 4 
    [10.000, 15.000) = 12 
    [15.000, 20.000) = 198 
    [20.000, 25.000) = 834 
    [25.000, 30.000) = 171 
    [30.000, 35.000) = 32 
    [35.000, 40.000) = 100 
    [40.000, 45.000) = 23 

  Percentiles, ms/op:
      p(0.0000) =      3.531 ms/op
     p(50.0000) =     21.823 ms/op
     p(90.0000) =     34.315 ms/op
     p(95.0000) =     36.064 ms/op
     p(99.0000) =     40.632 ms/op
     p(99.9000) =     41.540 ms/op
     p(99.9900) =     41.812 ms/op
     p(99.9990) =     41.812 ms/op
     p(99.9999) =     41.812 ms/op
    p(100.0000) =     41.812 ms/op


# Run complete. Total time: 00:01:30

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.275          ops/ms
Client.existUser                       thrpt         4.484          ops/ms
Client.getUser                         thrpt         3.825          ops/ms
Client.listUser                        thrpt         1.040          ops/ms
Client.createUser                       avgt        16.319           ms/op
Client.existUser                        avgt         5.956           ms/op
Client.getUser                          avgt         5.705           ms/op
Client.listUser                         avgt        22.426           ms/op
Client.createUser                     sample  3719   8.602 ± 0.242   ms/op
Client.createUser:createUser·p0.00    sample         3.052           ms/op
Client.createUser:createUser·p0.50    sample         7.897           ms/op
Client.createUser:createUser·p0.90    sample        13.271           ms/op
Client.createUser:createUser·p0.95    sample        17.105           ms/op
Client.createUser:createUser·p0.99    sample        22.479           ms/op
Client.createUser:createUser·p0.999   sample        47.055           ms/op
Client.createUser:createUser·p0.9999  sample        47.383           ms/op
Client.createUser:createUser·p1.00    sample        47.383           ms/op
Client.existUser                      sample  7205   4.449 ± 0.107   ms/op
Client.existUser:existUser·p0.00      sample         1.284           ms/op
Client.existUser:existUser·p0.50      sample         3.903           ms/op
Client.existUser:existUser·p0.90      sample         5.931           ms/op
Client.existUser:existUser·p0.95      sample         9.105           ms/op
Client.existUser:existUser·p0.99      sample        15.614           ms/op
Client.existUser:existUser·p0.999     sample        30.474           ms/op
Client.existUser:existUser·p0.9999    sample        30.999           ms/op
Client.existUser:existUser·p1.00      sample        30.999           ms/op
Client.getUser                        sample  4995   6.396 ± 0.107   ms/op
Client.getUser:getUser·p0.00          sample         1.569           ms/op
Client.getUser:getUser·p0.50          sample         5.833           ms/op
Client.getUser:getUser·p0.90          sample         8.870           ms/op
Client.getUser:getUser·p0.95          sample         9.667           ms/op
Client.getUser:getUser·p0.99          sample        14.385           ms/op
Client.getUser:getUser·p0.999         sample        25.985           ms/op
Client.getUser:getUser·p0.9999        sample        26.247           ms/op
Client.getUser:getUser·p1.00          sample        26.247           ms/op
Client.listUser                       sample  1376  23.410 ± 0.493   ms/op
Client.listUser:listUser·p0.00        sample         3.531           ms/op
Client.listUser:listUser·p0.50        sample        21.823           ms/op
Client.listUser:listUser·p0.90        sample        34.315           ms/op
Client.listUser:listUser·p0.95        sample        36.064           ms/op
Client.listUser:listUser·p0.99        sample        40.632           ms/op
Client.listUser:listUser·p0.999       sample        41.540           ms/op
Client.listUser:listUser·p0.9999      sample        41.812           ms/op
Client.listUser:listUser·p1.00        sample        41.812           ms/op
