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
# Warmup Iteration   1: 0.778 ops/ms
Iteration   1: 1.819 ops/ms


Result "org.apache.dubbo.benchmark.Client.createUser":
  1.819 ops/ms


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

# Run progress: 8.33% complete, ETA 00:01:24
# Fork: 1 of 1
# Warmup Iteration   1: 1.804 ops/ms
Iteration   1: 4.495 ops/ms


Result "org.apache.dubbo.benchmark.Client.existUser":
  4.495 ops/ms


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

# Run progress: 16.67% complete, ETA 00:01:15
# Fork: 1 of 1
# Warmup Iteration   1: 1.359 ops/ms
Iteration   1: 3.512 ops/ms


Result "org.apache.dubbo.benchmark.Client.getUser":
  3.512 ops/ms


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

# Run progress: 25.00% complete, ETA 00:01:08
# Fork: 1 of 1
# Warmup Iteration   1: 0.662 ops/ms
Iteration   1: 0.905 ops/ms


Result "org.apache.dubbo.benchmark.Client.listUser":
  0.905 ops/ms


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

# Run progress: 33.33% complete, ETA 00:01:00
# Fork: 1 of 1
# Warmup Iteration   1: 25.926 ±(99.9%) 0.673 ms/op
Iteration   1: 12.571 ±(99.9%) 0.078 ms/op


Result "org.apache.dubbo.benchmark.Client.createUser":
  12.571 ms/op


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

# Run progress: 41.67% complete, ETA 00:00:53
# Fork: 1 of 1
# Warmup Iteration   1: 14.567 ±(99.9%) 0.208 ms/op
Iteration   1: 6.387 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.Client.existUser":
  6.387 ms/op


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

# Run progress: 50.00% complete, ETA 00:00:45
# Fork: 1 of 1
# Warmup Iteration   1: 18.996 ±(99.9%) 0.243 ms/op
Iteration   1: 7.549 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.Client.getUser":
  7.549 ms/op


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
# Warmup Iteration   1: 35.884 ±(99.9%) 0.823 ms/op
Iteration   1: 25.488 ±(99.9%) 0.311 ms/op


Result "org.apache.dubbo.benchmark.Client.listUser":
  25.488 ms/op


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

# Run progress: 66.67% complete, ETA 00:00:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.774 ±(99.9%) 0.613 ms/op
Iteration   1: 9.571 ±(99.9%) 0.273 ms/op
                 createUser·p0.00:   3.420 ms/op
                 createUser·p0.50:   8.667 ms/op
                 createUser·p0.90:   11.059 ms/op
                 createUser·p0.95:   17.072 ms/op
                 createUser·p0.99:   31.051 ms/op
                 createUser·p0.999:  46.072 ms/op
                 createUser·p0.9999: 46.072 ms/op
                 createUser·p1.00:   46.072 ms/op



Result "org.apache.dubbo.benchmark.Client.createUser":
  N = 3339
  mean =      9.571 ±(99.9%) 0.273 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 22 
    [ 5.000, 10.000) = 2935 
    [10.000, 15.000) = 201 
    [15.000, 20.000) = 56 
    [20.000, 25.000) = 30 
    [25.000, 30.000) = 31 
    [30.000, 35.000) = 33 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 2 

  Percentiles, ms/op:
      p(0.0000) =      3.420 ms/op
     p(50.0000) =      8.667 ms/op
     p(90.0000) =     11.059 ms/op
     p(95.0000) =     17.072 ms/op
     p(99.0000) =     31.051 ms/op
     p(99.9000) =     46.072 ms/op
     p(99.9900) =     46.072 ms/op
     p(99.9990) =     46.072 ms/op
     p(99.9999) =     46.072 ms/op
    p(100.0000) =     46.072 ms/op


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
# Warmup Iteration   1: 12.798 ±(99.9%) 0.500 ms/op
Iteration   1: 6.652 ±(99.9%) 0.118 ms/op
                 existUser·p0.00:   1.010 ms/op
                 existUser·p0.50:   6.455 ms/op
                 existUser·p0.90:   7.642 ms/op
                 existUser·p0.95:   8.389 ms/op
                 existUser·p0.99:   20.387 ms/op
                 existUser·p0.999:  25.192 ms/op
                 existUser·p0.9999: 26.411 ms/op
                 existUser·p1.00:   26.411 ms/op



Result "org.apache.dubbo.benchmark.Client.existUser":
  N = 4820
  mean =      6.652 ±(99.9%) 0.118 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 65 
    [ 2.500,  5.000) = 510 
    [ 5.000,  7.500) = 3719 
    [ 7.500, 10.000) = 332 
    [10.000, 12.500) = 24 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 23 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.010 ms/op
     p(50.0000) =      6.455 ms/op
     p(90.0000) =      7.642 ms/op
     p(95.0000) =      8.389 ms/op
     p(99.0000) =     20.387 ms/op
     p(99.9000) =     25.192 ms/op
     p(99.9900) =     26.411 ms/op
     p(99.9990) =     26.411 ms/op
     p(99.9999) =     26.411 ms/op
    p(100.0000) =     26.411 ms/op


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

# Run progress: 83.33% complete, ETA 00:00:15
# Fork: 1 of 1
# Warmup Iteration   1: 13.035 ±(99.9%) 0.403 ms/op
Iteration   1: 6.648 ±(99.9%) 0.238 ms/op
                 getUser·p0.00:   1.014 ms/op
                 getUser·p0.50:   5.669 ms/op
                 getUser·p0.90:   8.333 ms/op
                 getUser·p0.95:   10.659 ms/op
                 getUser·p0.99:   28.151 ms/op
                 getUser·p0.999:  59.644 ms/op
                 getUser·p0.9999: 77.988 ms/op
                 getUser·p1.00:   77.988 ms/op



Result "org.apache.dubbo.benchmark.Client.getUser":
  N = 4888
  mean =      6.648 ±(99.9%) 0.238 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 693 
    [ 5.000, 10.000) = 3885 
    [10.000, 15.000) = 203 
    [15.000, 20.000) = 23 
    [20.000, 25.000) = 4 
    [25.000, 30.000) = 41 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 1 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 20 
    [55.000, 60.000) = 8 
    [60.000, 65.000) = 0 
    [65.000, 70.000) = 1 
    [70.000, 75.000) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.014 ms/op
     p(50.0000) =      5.669 ms/op
     p(90.0000) =      8.333 ms/op
     p(95.0000) =     10.659 ms/op
     p(99.0000) =     28.151 ms/op
     p(99.9000) =     59.644 ms/op
     p(99.9900) =     77.988 ms/op
     p(99.9990) =     77.988 ms/op
     p(99.9999) =     77.988 ms/op
    p(100.0000) =     77.988 ms/op


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
# Warmup Iteration   1: 38.897 ±(99.9%) 1.525 ms/op
Iteration   1: 25.621 ±(99.9%) 0.636 ms/op
                 listUser·p0.00:   12.468 ms/op
                 listUser·p0.50:   23.233 ms/op
                 listUser·p0.90:   36.045 ms/op
                 listUser·p0.95:   37.585 ms/op
                 listUser·p0.99:   42.172 ms/op
                 listUser·p0.999:  46.121 ms/op
                 listUser·p0.9999: 46.924 ms/op
                 listUser·p1.00:   46.924 ms/op



Result "org.apache.dubbo.benchmark.Client.listUser":
  N = 1249
  mean =     25.621 ±(99.9%) 0.636 ms/op

  Histogram, ms/op:
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 255 
    [20.000, 22.500) = 254 
    [22.500, 25.000) = 223 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 77 
    [32.500, 35.000) = 112 
    [35.000, 37.500) = 110 
    [37.500, 40.000) = 37 
    [40.000, 42.500) = 23 
    [42.500, 45.000) = 3 
    [45.000, 47.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =     12.468 ms/op
     p(50.0000) =     23.233 ms/op
     p(90.0000) =     36.045 ms/op
     p(95.0000) =     37.585 ms/op
     p(99.0000) =     42.172 ms/op
     p(99.9000) =     46.121 ms/op
     p(99.9900) =     46.924 ms/op
     p(99.9990) =     46.924 ms/op
     p(99.9999) =     46.924 ms/op
    p(100.0000) =     46.924 ms/op


# Run complete. Total time: 00:01:31

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                               Mode   Cnt   Score   Error   Units
Client.createUser                      thrpt         1.819          ops/ms
Client.existUser                       thrpt         4.495          ops/ms
Client.getUser                         thrpt         3.512          ops/ms
Client.listUser                        thrpt         0.905          ops/ms
Client.createUser                       avgt        12.571           ms/op
Client.existUser                        avgt         6.387           ms/op
Client.getUser                          avgt         7.549           ms/op
Client.listUser                         avgt        25.488           ms/op
Client.createUser                     sample  3339   9.571 ± 0.273   ms/op
Client.createUser:createUser·p0.00    sample         3.420           ms/op
Client.createUser:createUser·p0.50    sample         8.667           ms/op
Client.createUser:createUser·p0.90    sample        11.059           ms/op
Client.createUser:createUser·p0.95    sample        17.072           ms/op
Client.createUser:createUser·p0.99    sample        31.051           ms/op
Client.createUser:createUser·p0.999   sample        46.072           ms/op
Client.createUser:createUser·p0.9999  sample        46.072           ms/op
Client.createUser:createUser·p1.00    sample        46.072           ms/op
Client.existUser                      sample  4820   6.652 ± 0.118   ms/op
Client.existUser:existUser·p0.00      sample         1.010           ms/op
Client.existUser:existUser·p0.50      sample         6.455           ms/op
Client.existUser:existUser·p0.90      sample         7.642           ms/op
Client.existUser:existUser·p0.95      sample         8.389           ms/op
Client.existUser:existUser·p0.99      sample        20.387           ms/op
Client.existUser:existUser·p0.999     sample        25.192           ms/op
Client.existUser:existUser·p0.9999    sample        26.411           ms/op
Client.existUser:existUser·p1.00      sample        26.411           ms/op
Client.getUser                        sample  4888   6.648 ± 0.238   ms/op
Client.getUser:getUser·p0.00          sample         1.014           ms/op
Client.getUser:getUser·p0.50          sample         5.669           ms/op
Client.getUser:getUser·p0.90          sample         8.333           ms/op
Client.getUser:getUser·p0.95          sample        10.659           ms/op
Client.getUser:getUser·p0.99          sample        28.151           ms/op
Client.getUser:getUser·p0.999         sample        59.644           ms/op
Client.getUser:getUser·p0.9999        sample        77.988           ms/op
Client.getUser:getUser·p1.00          sample        77.988           ms/op
Client.listUser                       sample  1249  25.621 ± 0.636   ms/op
Client.listUser:listUser·p0.00        sample        12.468           ms/op
Client.listUser:listUser·p0.50        sample        23.233           ms/op
Client.listUser:listUser·p0.90        sample        36.045           ms/op
Client.listUser:listUser·p0.95        sample        37.585           ms/op
Client.listUser:listUser·p0.99        sample        42.172           ms/op
Client.listUser:listUser·p0.999       sample        46.121           ms/op
Client.listUser:listUser·p0.9999      sample        46.924           ms/op
Client.listUser:listUser·p1.00        sample        46.924           ms/op
