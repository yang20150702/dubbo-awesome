# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.223 ops/ms
# Warmup Iteration   2: 2.742 ops/ms
# Warmup Iteration   3: 5.990 ops/ms
Iteration   1: 5.994 ops/ms
Iteration   2: 6.368 ops/ms
Iteration   3: 6.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.189 ±(99.9%) 3.423 ops/ms [Average]
  (min, avg, max) = (5.994, 6.189, 6.368), stdev = 0.188
  CI (99.9%): [2.766, 9.611] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.676 ops/ms
# Warmup Iteration   2: 5.431 ops/ms
# Warmup Iteration   3: 6.303 ops/ms
Iteration   1: 6.529 ops/ms
Iteration   2: 6.621 ops/ms
Iteration   3: 6.298 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.482 ±(99.9%) 3.040 ops/ms [Average]
  (min, avg, max) = (6.298, 6.482, 6.621), stdev = 0.167
  CI (99.9%): [3.443, 9.522] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.568 ops/ms
# Warmup Iteration   2: 4.832 ops/ms
# Warmup Iteration   3: 6.237 ops/ms
Iteration   1: 6.238 ops/ms
Iteration   2: 6.058 ops/ms
Iteration   3: 6.107 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.135 ±(99.9%) 1.698 ops/ms [Average]
  (min, avg, max) = (6.058, 6.135, 6.238), stdev = 0.093
  CI (99.9%): [4.436, 7.833] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.694 ops/ms
# Warmup Iteration   2: 4.471 ops/ms
# Warmup Iteration   3: 5.327 ops/ms
Iteration   1: 5.285 ops/ms
Iteration   2: 5.418 ops/ms
Iteration   3: 5.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.405 ±(99.9%) 2.091 ops/ms [Average]
  (min, avg, max) = (5.285, 5.405, 5.514), stdev = 0.115
  CI (99.9%): [3.315, 7.496] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 17.616 ±(99.9%) 0.090 ms/op
# Warmup Iteration   2: 6.056 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.442 ±(99.9%) 0.012 ms/op
Iteration   1: 5.153 ±(99.9%) 0.011 ms/op
Iteration   2: 5.151 ±(99.9%) 0.019 ms/op
Iteration   3: 5.238 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.181 ±(99.9%) 0.907 ms/op [Average]
  (min, avg, max) = (5.151, 5.181, 5.238), stdev = 0.050
  CI (99.9%): [4.274, 6.088] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.079 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.672 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.159 ±(99.9%) 0.006 ms/op
Iteration   1: 4.873 ±(99.9%) 0.006 ms/op
Iteration   2: 4.971 ±(99.9%) 0.005 ms/op
Iteration   3: 4.925 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.923 ±(99.9%) 0.897 ms/op [Average]
  (min, avg, max) = (4.873, 4.923, 4.971), stdev = 0.049
  CI (99.9%): [4.026, 5.819] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.036 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 6.504 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.319 ±(99.9%) 0.008 ms/op
Iteration   1: 5.222 ±(99.9%) 0.012 ms/op
Iteration   2: 5.100 ±(99.9%) 0.008 ms/op
Iteration   3: 5.153 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.159 ±(99.9%) 1.114 ms/op [Average]
  (min, avg, max) = (5.100, 5.159, 5.222), stdev = 0.061
  CI (99.9%): [4.044, 6.273] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 16.563 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.724 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.793 ±(99.9%) 0.010 ms/op
Iteration   1: 5.928 ±(99.9%) 0.009 ms/op
Iteration   2: 5.853 ±(99.9%) 0.013 ms/op
Iteration   3: 5.868 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.883 ±(99.9%) 0.719 ms/op [Average]
  (min, avg, max) = (5.853, 5.883, 5.928), stdev = 0.039
  CI (99.9%): [5.164, 6.602] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.082 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 6.155 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.550 ±(99.9%) 0.027 ms/op
Iteration   1: 5.235 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   4.874 ms/op
                 createUser·p0.90:   6.423 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   11.567 ms/op
                 createUser·p0.999:  22.206 ms/op
                 createUser·p0.9999: 25.490 ms/op
                 createUser·p1.00:   29.032 ms/op

Iteration   2: 5.181 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.159 ms/op
                 createUser·p0.50:   4.833 ms/op
                 createUser·p0.90:   6.390 ms/op
                 createUser·p0.95:   7.447 ms/op
                 createUser·p0.99:   10.912 ms/op
                 createUser·p0.999:  23.303 ms/op
                 createUser·p0.9999: 27.508 ms/op
                 createUser·p1.00:   31.621 ms/op

Iteration   3: 5.336 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.474 ms/op
                 createUser·p0.50:   4.997 ms/op
                 createUser·p0.90:   6.668 ms/op
                 createUser·p0.95:   7.569 ms/op
                 createUser·p0.99:   10.748 ms/op
                 createUser·p0.999:  25.461 ms/op
                 createUser·p0.9999: 29.296 ms/op
                 createUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 182763
  mean =      5.250 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40 
    [ 2.500,  5.000) = 104330 
    [ 5.000,  7.500) = 68664 
    [ 7.500, 10.000) = 6824 
    [10.000, 12.500) = 1783 
    [12.500, 15.000) = 725 
    [15.000, 17.500) = 157 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 34 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.474 ms/op
     p(50.0000) =      4.882 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.610 ms/op
     p(99.0000) =     11.131 ms/op
     p(99.9000) =     22.884 ms/op
     p(99.9900) =     28.734 ms/op
     p(99.9990) =     30.102 ms/op
     p(99.9999) =     31.621 ms/op
    p(100.0000) =     31.621 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.835 ±(99.9%) 0.296 ms/op
# Warmup Iteration   2: 5.463 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.183 ±(99.9%) 0.018 ms/op
Iteration   1: 4.958 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   0.455 ms/op
                 existUser·p0.50:   4.604 ms/op
                 existUser·p0.90:   6.111 ms/op
                 existUser·p0.95:   7.127 ms/op
                 existUser·p0.99:   10.584 ms/op
                 existUser·p0.999:  20.558 ms/op
                 existUser·p0.9999: 32.673 ms/op
                 existUser·p1.00:   34.406 ms/op

Iteration   2: 4.958 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   2.101 ms/op
                 existUser·p0.50:   4.669 ms/op
                 existUser·p0.90:   5.947 ms/op
                 existUser·p0.95:   7.012 ms/op
                 existUser·p0.99:   10.453 ms/op
                 existUser·p0.999:  23.101 ms/op
                 existUser·p0.9999: 26.054 ms/op
                 existUser·p1.00:   26.575 ms/op

Iteration   3: 4.916 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   0.461 ms/op
                 existUser·p0.50:   4.645 ms/op
                 existUser·p0.90:   5.931 ms/op
                 existUser·p0.95:   6.586 ms/op
                 existUser·p0.99:   9.224 ms/op
                 existUser·p0.999:  17.002 ms/op
                 existUser·p0.9999: 28.557 ms/op
                 existUser·p1.00:   29.295 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 193994
  mean =      4.944 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 136634 
    [ 5.000,  7.500) = 50586 
    [ 7.500, 10.000) = 4730 
    [10.000, 12.500) = 1173 
    [12.500, 15.000) = 399 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 18 
    [30.000, 32.500) = 21 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.455 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.005 ms/op
     p(95.0000) =      6.881 ms/op
     p(99.0000) =     10.043 ms/op
     p(99.9000) =     19.071 ms/op
     p(99.9900) =     31.896 ms/op
     p(99.9990) =     34.037 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 16.823 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 6.832 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.665 ±(99.9%) 0.028 ms/op
Iteration   1: 5.571 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   0.552 ms/op
                 getUser·p0.50:   5.226 ms/op
                 getUser·p0.90:   7.070 ms/op
                 getUser·p0.95:   8.307 ms/op
                 getUser·p0.99:   11.911 ms/op
                 getUser·p0.999:  21.576 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   27.361 ms/op

Iteration   2: 5.423 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.134 ms/op
                 getUser·p0.50:   4.882 ms/op
                 getUser·p0.90:   7.234 ms/op
                 getUser·p0.95:   8.749 ms/op
                 getUser·p0.99:   12.845 ms/op
                 getUser·p0.999:  18.253 ms/op
                 getUser·p0.9999: 27.692 ms/op
                 getUser·p1.00:   29.360 ms/op

Iteration   3: 5.293 ±(99.9%) 0.024 ms/op
                 getUser·p0.00:   2.359 ms/op
                 getUser·p0.50:   4.858 ms/op
                 getUser·p0.90:   6.586 ms/op
                 getUser·p0.95:   7.741 ms/op
                 getUser·p0.99:   11.649 ms/op
                 getUser·p0.999:  29.297 ms/op
                 getUser·p0.9999: 47.635 ms/op
                 getUser·p1.00:   48.628 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 176970
  mean =      5.427 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 91602 
    [ 5.000, 10.000) = 81437 
    [10.000, 15.000) = 3376 
    [15.000, 20.000) = 380 
    [20.000, 25.000) = 70 
    [25.000, 30.000) = 51 
    [30.000, 35.000) = 22 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.552 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.898 ms/op
     p(95.0000) =      8.274 ms/op
     p(99.0000) =     12.091 ms/op
     p(99.9000) =     19.792 ms/op
     p(99.9900) =     45.974 ms/op
     p(99.9990) =     48.325 ms/op
     p(99.9999) =     48.628 ms/op
    p(100.0000) =     48.628 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 17.905 ±(99.9%) 0.309 ms/op
# Warmup Iteration   2: 6.909 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.210 ±(99.9%) 0.024 ms/op
Iteration   1: 5.959 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.019 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   7.201 ms/op
                 listUser·p0.95:   8.782 ms/op
                 listUser·p0.99:   12.681 ms/op
                 listUser·p0.999:  26.739 ms/op
                 listUser·p0.9999: 31.966 ms/op
                 listUser·p1.00:   32.735 ms/op

Iteration   2: 5.819 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.649 ms/op
                 listUser·p0.50:   5.505 ms/op
                 listUser·p0.90:   6.824 ms/op
                 listUser·p0.95:   7.717 ms/op
                 listUser·p0.99:   10.846 ms/op
                 listUser·p0.999:  26.345 ms/op
                 listUser·p0.9999: 30.557 ms/op
                 listUser·p1.00:   32.965 ms/op

Iteration   3: 6.036 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.810 ms/op
                 listUser·p0.50:   5.726 ms/op
                 listUser·p0.90:   7.193 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   11.577 ms/op
                 listUser·p0.999:  20.251 ms/op
                 listUser·p0.9999: 22.492 ms/op
                 listUser·p1.00:   23.658 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 161673
  mean =      5.937 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 18168 
    [ 5.000,  7.500) = 131435 
    [ 7.500, 10.000) = 8602 
    [10.000, 12.500) = 2248 
    [12.500, 15.000) = 668 
    [15.000, 17.500) = 138 
    [17.500, 20.000) = 116 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 96 
    [27.500, 30.000) = 42 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.649 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.258 ms/op
     p(99.0000) =     11.715 ms/op
     p(99.9000) =     25.111 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     32.823 ms/op
     p(99.9999) =     32.965 ms/op
    p(100.0000) =     32.965 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.189 ± 3.423  ops/ms
ClientPb.existUser                       thrpt       3   6.482 ± 3.040  ops/ms
ClientPb.getUser                         thrpt       3   6.135 ± 1.698  ops/ms
ClientPb.listUser                        thrpt       3   5.405 ± 2.091  ops/ms
ClientPb.createUser                       avgt       3   5.181 ± 0.907   ms/op
ClientPb.existUser                        avgt       3   4.923 ± 0.897   ms/op
ClientPb.getUser                          avgt       3   5.159 ± 1.114   ms/op
ClientPb.listUser                         avgt       3   5.883 ± 0.719   ms/op
ClientPb.createUser                     sample  182763   5.250 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.474           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.882           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.521           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.610           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.131           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.884           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.734           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.621           ms/op
ClientPb.existUser                      sample  193994   4.944 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.455           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.637           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.043           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.071           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.896           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.406           ms/op
ClientPb.getUser                        sample  176970   5.427 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.552           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.898           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.274           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.091           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.792           ms/op
ClientPb.getUser:getUser·p0.9999        sample          45.974           ms/op
ClientPb.getUser:getUser·p1.00          sample          48.628           ms/op
ClientPb.listUser                       sample  161673   5.937 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.649           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.258           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.715           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.111           ms/op
ClientPb.listUser:listUser·p0.9999      sample          31.162           ms/op
ClientPb.listUser:listUser·p1.00        sample          32.965           ms/op
